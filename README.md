### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> Self in Nix
```nix
{ pkgs
, ...
}: {
  users.users.iosmanthus = {
    interest = [
      "Cat"
      "Database"
      "Distributed System"
      "NixOS"
      "Rust"
    ];

    careers = [{
      name = "PingCAP";
      url = "https://www.pingcap.com";
    }];

    contact = {
      email = "myosmanthustree@gmail.com";
      twitter = "@iosmanthus1998";
    };

    tools = {
      editor = pkgs.vscode;
      shell = pkgs.zsh;
      terminal = pkgs.kitty;
      browser = pkgs.firefox;
      font = pkgs.meslo-lg;
      email = pkgs.thunderbird;
    };

    tags = [ "hen-pecked" "cat lover" ];
  };
}
```
### Listening
[![Apple Music GitHub profile](https://music-profile.rayriffy.com/theme/light.svg?uid=001894.8d59bcfc30354aefab4412215c6166a3.0701)](https://github.com/rayriffy/apple-music-github-profile)
