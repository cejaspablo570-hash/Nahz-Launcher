Nahz Launcher

EN: A free, non-commercial, open-source launcher for Minecraft: Java Edition, built with Electron and React. It signs in owners of the game with their Microsoft account, installs game versions and mod loaders with hash verification, and manages mods, resource packs, shaders and worlds.

ES: Launcher gratuito, no comercial y de código abierto para Minecraft: Java Edition, hecho con Electron y React. Inicia sesión con la cuenta Microsoft del dueño del juego, instala versiones y loaders con verificación de hashes y gestiona mods, resource packs, shaders y mundos.

Nahz Launcher is not affiliated with, endorsed by or associated with Mojang Studios, Microsoft or CurseForge. "Minecraft" is a trademark of Mojang Studios. Nahz Launcher no está afiliado a Mojang Studios, Microsoft ni CurseForge.

Características / Features
Login Microsoft / Xbox / Minecraft Services (device code flow). It checks that the account owns Minecraft Java Edition.
Tokens cifrados: stored encrypted with Electron safeStorage (DPAPI on Windows, Keychain on macOS). They are never exposed to the UI and never stored in plain text.
Instalador con hashes: vanilla (SHA-1 from Mojang), Fabric and Quilt (SHA-1 from the maven), Forge and NeoForge (official installer, verified). Downloads without a hash are rejected, and only allow-listed hosts are used.
Mods, resource packs y shaders from Modrinth (SHA-512) and CurseForge (SHA-1, requires API key). Required dependencies are installed automatically; mods can be enabled or disabled.
Mundos: list, open folder, zip backup, delete.
Offline profiles for testing and offline servers.
Java auto-detection, RAM, JVM arguments, resolution and crash diagnostics.
Privacidad / Privacy

No analytics, no telemetry, no own servers. The launcher only talks to Microsoft/Xbox/Mojang (login), Mojang and loader maintainers (downloads), and Modrinth/CurseForge (content). Account data stays on your device.

Sin analíticas ni telemetría ni servidores propios. Los datos de tu cuenta se quedan en tu equipo.
