# Overseer



---

⠀⠀⠀⠀⠀⠀⠀⣀⣤⣶⣾⣿⣿⣿⣿⣿⣿⣷⣶⣤⣀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⣠⣾⡿⠋⣽⣿⡿⠋⠉⠀⠀⠉⠙⢿⣿⣏⠻⣿⣦⡀⠀⠀⠀
⠀⠀⣰⣿⡟⠁⠀⣼⣿⠏⠀⠀⢀⣤⣤⡀⠀⠀⢻⣿⣧⠀⠈⢿⣷⡀⠀
⢀⣾⣟⠁⠀⠀⢸⣿⣿⠀⠀⠀⢿⣿⣿⡿⠀⠀⠀⣿⣿⡇⠀⠀⠙⣿⣆
⠀⠹⣿⣷⣄⠀⠈⣿⣿⣆⠀⠀⠀⠉⠉⠀⠀⠀⣸⣿⣿⠁⠀⢀⣾⣿⠏
⠀⠀⠀⠙⠻⣿⣦⡈⢿⣿⣷⣄⠀⠀⠀⢀⣠⣾⣿⡿⢁⣠⣾⡿⠋⠀⠀
⠀⠀⠀⠀⠀⠀⠈⠙⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠿⠛⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
                                                                  
                                                                  
 ---                                                                 














**Overseer** is sooooo cool

---

### What it does

Overseer checks the last time the game was updated and checks it against the last set date.  

- If the dates match → the script is marked as **safe** (`OVERSEER_SAFE = true`)
- If the dates do **not** match → the script is marked as **unsafe** (`OVERSEER_SAFE = false`) and a warning is shown

This allows devs to lock features until they themself have checked them.
To lock features wrap them in an if statement checking for OVERSEER_SAFE.

Example:

if OVERSEER_SAFE == true then print("Yay not patched") else print("Waiting for developer to check") end


---

### Why it's useful

Games may patch features or vulnerabilities in updates so overseer is useful for preventing bans of many users and not ruining your reputation.

Overseer forces developers to actually manually update and check features, if it is marked as safe and a feature gets you banned they did not check properly.

This is useful for:
- Scripts that rely on vulnerabilities
- Features that may become a risk for bans even simple flies if the game adds a simple anti cheat
---

### Extra macros

--// OVERSEER_CHECK can be ran with or after overseer has loaded and sets the clipboard to the new value that you use to replace the old one.
OVERSEER_CHECK() 

                                            
