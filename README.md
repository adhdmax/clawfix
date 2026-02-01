# clawfix
🦞 Quick fix tool for OpenClaw (formerly Clawdbot) gateway issues on macOS# ClawFix 🦞

Quick repair tool for your OpenClaw gateway.

*For OpenClaw (formerly Clawdbot)*

## One-Line Install

```bash
curl -fsSL https://raw.githubusercontent.com/adhdmax/clawfix/main/install.sh | bash
```

## What It Fixes

- ✅ Gateway not running → Restarts it
- - ✅ Session overflow → Clears old sessions
  - - ✅ Context overflow → Clears history when token limit exceeded
    - - ✅ Security issues → Warns if exposed to network
     
      - ## Usage
     
      - ```bash
        clawfix
        ```

        That's it. Run when things break.

        ## Sample Output

        ```
           ____ _              _____ _
          / ___| | __ ___    __|  ___(_)_  __
         | |   | |/ _` \ \ /\ / /| |_  | \ \/ /
         | |___| | (_| |\ V  V / |  _| | |>  <
          \____|_|\__,_| \_/\_/  |_|   |_/_/\_\
             Keeps Your Claws Up & Running 🦞

        Checking gateway process... ✓ Running
        Checking port 18789... ✓ Listening
        Checking sessions (12)... ✓ OK
        Checking context overflow... ✓ OK
        Checking security... ✓ Local only

        All checks passed! 🦞
        ```

        ## Want Auto-Monitoring?

        **[ClawFix Pro](https://bit.ly/clawfix-pro)** runs in the background 24/7:

        | Feature | Free | Pro |
        |---------|------|-----|
        | One-command fix | ✅ | ✅ |
        | Session clearing | ✅ | ✅ |
        | Context overflow fix | ✅ | ✅ |
        | Background monitoring | ❌ | ✅ |
        | Auto-fix on failure | ❌ | ✅ |
        | Detailed logging | ❌ | ✅ |
        | Auto-start on login | ❌ | ✅ |

        **$4.99 one-time** → [Get ClawFix Pro](https://bit.ly/clawfix-pro)

        ## Compatibility

        - macOS (Apple Silicon & Intel)
        - - OpenClaw (latest)
          - - Clawdbot (legacy)
            - - All channels: WhatsApp, Telegram, Discord, Slack, iMessage
             
              - ## License
             
              - MIT
             
              - ---

              Made for the OpenClaw community 🦞
