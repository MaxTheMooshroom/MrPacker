
## Mr. Packer

<!-- TODO: "The_Minecraft_Bee_is_Trans.png" -->
<!-- ![Minecraft Bee is trans]() -->
<img src="https://pbs.twimg.com/media/Ex0_hK_WYAEKa4w?format=png&name=small" style="width:200px;"></img>

* Disclaimer: This project is not in any capacity involved with
[Modrinth](https://modrinth.com/) or the Modrinth team. This is
purely a labor of love for the modding community, and the Modrinth
platform in particular (sans some shortcomings).

<hr />

Mr. Packer (Modrinth Packer, affectionately called "Mister Packer") is a graphical tool that
aims to create a cross-platform GUI for modpack development. It's called "Mr. Packer" because
of the file format "mrpack" generated by
[Modrinth's Theseus App](https://github.com/modrinth/code/blob/main/apps/app/README.md)
when exporting a created modpack, and it's used for packing a bunch of resources together
for an enhanced minecraft experience.

### TODO

- [ ] base functionality
    - [ ] add a pack viewer
        - [ ] add a mod viewer
            - [ ] markdown renderer
            - [ ] version selector
        - [ ] add a config modifier
            - [ ] client config
            - [ ] common config
            - [ ] server config
        - [ ] add a recipe modifier
        - [ ] add a datapack viewer
        - [ ] add a resourcepack viewer
    - [ ] generate separate server and client mrpacks (and a merged mrpack)
    - [ ] perform pack validation to look for any incompatibilities, dependency issues,
          and any other issue that may arise during pack development
    - [ ] address incorrect "env" variables for mod files in theseus' generated mrpacks
    - [ ] generate changelogs from one version to the next
    - [ ] add a mod validator
        - [ ] validate 'mods.toml' for forge
            - [ ] dependency validator
                - [ ] version string validator
        - [ ] validate '\<???>.\<???>' for fabric



### Milestones

- [ ] get a basic blockout graphic design for Mr. Packer done in figma (WIP)
- [ ] design the application state
- [ ] design the application messages
- [ ] design the application renderer
- [ ] design the application update logic
