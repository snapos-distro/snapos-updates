# SnapOS updates

> [!IMPORTANT]
> **Despite the name, SnapOS does not use Snap!** No Snap packages and no snapd. The name comes from the
> alligator snapping turtle, our mascot Snappy. Programs come from Nix, with Flatpak and `.deb` files if you want them.

Installed SnapOS systems look here for updates. Each release carries only what `snapos update` needs:

- `snapos-release.txt`: the commit, version, name and date of the release
- `snapos-source.tar.gz` and its `.sha256`: the source the system is rebuilt from

The installer images are in [SnapOS](https://github.com/snapos-distro/SnapOS/releases). Every release here is a copy of a published, tested SnapOS release.
