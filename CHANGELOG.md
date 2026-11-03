# Changelog

## 0.2.0

- Accept Minecraft 1.20.1 Forge patch releases from 47.4.13 onward without an exact Forge 47.4.13 dependency pin.
- Align packaged mod metadata and artifact version to 0.2.0.
- Preserve dedicated-server-only behavior and existing UUID-based observer/vanish settings.
- CI exercises an isolated Forge 47.4.28 runtime fixture and synthetic vanilla-protocol clients, including hidden/visible player controls. Third-party modpack and admin-console integration remains a separate deployment gate.
