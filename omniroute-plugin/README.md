# OmniRoute plugin

Packages the agent skills from the OmniRoute repo (https://github.com/cheaper-inference/OmniRoute, MIT) as a Claude plugin.

- 23 API skills (`omni-*`) and 21 CLI skills (`cli-*`), plus a few extras.
- Start with `omni-auth` for REST access or `cli-serve` for CLI access.
- The skills drive a running OmniRoute server (default http://localhost:20128). Install and start OmniRoute separately.

Test locally: `claude --plugin-dir ./omniroute-plugin`
