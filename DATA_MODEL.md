# Vidu Radar Data Model 💾🚕

## Database Structure

The database stores driver information, vehicle data, location data and app records.

---

# 1. Drivers Collection 👤

Fields:

- driver_id
- name
- phone_number
- language
- created_date

---

# 2. Vehicles Collection 🚕

Fields:

- vehicle_id
- driver_id
- vehicle_type
- fuel_type
- fuel_price
- average_km_per_liter
- vehicle_number

---

# 3. Locations Collection 📍

Fields:

- location_id
- driver_id
- latitude
- longitude
- location_name
- saved_date

---

# 4. Hotspots Collection 🔥

Fields:

- hotspot_id
- location_name
- latitude
- longitude
- demand_level
- active_time
- rating

Demand:

- High
- Medium
- Good

---

# 5. Ride History Collection 📊

Fields:

- ride_id
- driver_id
- start_location
- destination
- distance
- duration
- fare
- date

---

# 6. Fuel Records Collection ⛽

Fields:

- fuel_id
- driver_id
- fuel_amount
- fuel_cost
- distance
- km_per_liter
- date

---

# 7. Earnings Collection 💰

Fields:

- earning_id
- driver_id
- total_income
- fuel_expense
- profit
- date

---

# 8. Service Locations Collection 🔧

Fields:

- service_id
- type
- name
- latitude
- longitude
- contact
- opening_hours

Types:

- Fuel station
- Bank
- Garage
- Tyre shop
- Spare parts
- Three-wheel repair

---

# 9. User Settings Collection ⚙️

Fields:

- language
- voice_settings
- map_settings
- notification_settings
- safety_settings

---

# Future Data Features 🚀

- AI demand prediction data
- Traffic information
- Driver community reports
- Offline synchronization
