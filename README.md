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
[![spotify-github-profile](https://spotify-github-profile.vercel.app/api/view?uid=myosmanthus&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=false)](https://github.com/kittinan/spotify-github-profile)