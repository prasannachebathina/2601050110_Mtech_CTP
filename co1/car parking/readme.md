Run the program to start the interactive management console. Below is a structured walkthrough based on standard execution logs.

### Application Menu Options
1. **View Current Slot Availability** — Checks total capacity and displays next vacant slot numbers.
2. **Park Incoming Vehicle (Check-In)** — Reserves the lowest available slot number for a unique license plate.
3. **Process Departing Vehicle (Check-Out)** — Frees up a slot and automatically generates a dynamic billing invoice.
4. **Exit Management Program** — Safely shuts down the management application.

---

### Step-by-Step Execution Flow

#### 1. Initial System Check (Option 1)
Query the empty parking directory to check current capacity limits before processing vehicle entry points.

* **User Input:** `1`
* **Console Output:**
```text
[STATUS] Available Slots: 100 / 100
Next vacant slots: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] ...
```

#### 2. Vehicle Check-In Process (Option 2)
Log an incoming vehicle by assigning its unique identification string to the lowest indexed empty node.

* **User Input:** `2`
* **Sub-prompt Input:** `3` (Vehicle License Number)
* **Console Output:**
```text
[SUCCESS] Vehicle 3 successfully parked in Slot #1.
```

#### 3. System Termination (Option 4)
Gracefully close active tracking operations and shut down host terminal runtime listeners.

* **User Input:** `4`
* **Console Output:**
```text
Shutting down console system. Goodbye!
```

