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
![https://github-profile-apple-music.web.app/api/v1/users/0x5OD3yn9djEXkI3rlxw/recent/played/tracks?template=template_1_3](https://github-profile-apple-music.web.app/api/v1/users/0x5OD3yn9djEXkI3rlxw/recent/played/tracks?template=template_1_3)