# KRNK_doublejump
double jump example for KrunkerScript

Instructions:
1. copy-paste & replace all text in doublejump_client.krnk / doublejump_host.krnk into client/host windows
2. click Validate or ctrl-s to save

3. OPTIONAL: to change settings like triplejump / refresh with walljump, change value on BOTH client and script settings:
    ```cs
    # ===================================================================
    # RECOMMENDED SETTINGS:
    num MAX_JUMPCOUNT = 2; # 2 is "doublejump", 3 is "triplejump"
    bool WALLJUMP_REFRESHS = true;
    bool ENABLE_CROUCHJUMP = true; # lower height for crouch jump, also
                                    # applies "moonjump" mid-air physics

    # HARD-CODED NUMBERS - DON'T TOUCH
    num MS_DURATION_UNCROUCH = 166;
    num HEIGHT_JUMP = 0.0793; # 60FPS, max clearance 17.9 units
    num HEIGHT_CROUCHJUMP = 0.0595; # 60FPS, max clearance 10.2 units
    # ===================================================================
    ```

gif example
https://streamable.com/gccxd1
