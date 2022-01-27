# KRNK_doublejump
**🏃‍♂️ Try for yourself here! https://krunker.io/?play=djumpexample**

Double-Jump example for KrunkerScript - https://streamable.com/gccxd1

Instructions:
1. copy-paste & replace all text in doublejump_client.krnk / doublejump_host.krnk into client/host windows
2. click Validate or ctrl-s to save

3. OPTIONAL: to change settings like triplejump / refresh with walljump, change value on BOTH client and host settings:
    ```cs
    # ===================================================================
    # SETTINGS:
    num MAX_JUMPCOUNT = 2; # 2 is "doublejump", 3 is "triplejump"
    bool WALLJUMP_REFRESHS = true;
    bool ENABLE_CROUCHJUMP = true; # lower height for crouch jump, also
                                    # applies "moonjump" mid-air physics
    num SOUND = 31960; # sound ID. set to 0 if no sound desired

    # HARD-CODED NUMBERS - DON'T TOUCH
    num MS_DURATION_UNCROUCH = 166;
    num HEIGHT_JUMP = 0.0793; # 60FPS, max clearance 17.9 units
    num HEIGHT_CROUCHJUMP = 0.0595; # 60FPS, max clearance 10.2 units
    # ===================================================================
    ```
