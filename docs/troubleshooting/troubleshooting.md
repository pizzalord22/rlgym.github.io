#### The game launches, but nothing else happens and no error is thrown.

You may not have enabled the RLGym plugin. From inside the game, press F2 to open the Bakkesmod menu and navigate to the `plugins` tab.
From there, open the `Plugin Manager` and scroll down to the RLGym plugin. Make sure the check box is ticked, close Rocket League, and try to create an RLGym environment again.

***

#### I installed RLGym through PIP, but the plugin does not appear in the Bakkesmod plugin manager.

For whatever reason, the plugin may not have installed appropriately. You can download a new version of the plugin from [here](https://github.com/lucas-emery/rocket-league-gym/tree/main/rlgym/plugin).
Once you have the plugin, navigate to the folder `AppData\Roaming\bakkesmod\bakkesmod\plugins` and move RLGym.dll there. Afterwards, launch Rocket League and check the Bakkesmod plugin manager again.

***

#### When I pass the steam install location of Rocket League to `rlgym.make()`, the game launches but nothing happens.

When launching through steam, do not pass the location of `RocketLeague.exe` to RLGym. The API will locate Steam automatically, and use that to launch the game for you.

***

#### I have both the Epic and Steam versions of Rocket League installed, but RLGym will only launch the Epic version.

RLGym will always launch the Epic version of Rocket League when it is able. Make sure to ping @Aech9835 in the RLBot Discord ceaselessly until this is fixed.
