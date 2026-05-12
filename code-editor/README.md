Edit your Home Assistant configuration files directly from
Home Assistant. 🎉

Code Editor is a browser-based VS Code editor powered by code-server, plus extensions
selected for Home Assistant configuration, ESPHome, YAML, Jinja templates,
Python, icons, and log files.

Open Code Editor from the Home Assistant sidebar after installation. Most users
can keep the default configuration, which opens `/config` and stores editor data
inside this app's persistent data folder.

Code Editor is served through Home Assistant ingress, runs code-server behind an
internal proxy, and includes an AppArmor profile to reduce the exposed runtime
surface while keeping the editor useful.

For configuration details, see the Documentation tab.
