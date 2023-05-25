### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> Self in Nix
```nix
{ pkgs
, ...
}: {
  users.users.iosmanthus = {
    tags = [
      {
        name = "怕老婆";
        alt = "hen-pecked";
      }
      {
        name = "猫奴";
        alt = "cat lover";
      }
    ];

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
  };
}
```
