
****************************************
Capernia Datapack: making the ultimate datapack for OTS (Open Tibia Server)
****************************************

Capernia Datapack is a project born from the necessity of a serious OTS files.
Its goal is to make sure all new Tibia resources be unified and ready for use on the latest version of Forgotten Server.


![Tibia 10.91 Sample](https://cloud.githubusercontent.com/assets/19177793/15003885/258236d8-1187-11e6-86fd-f83118992146.png)


Capernia Datapack is made using LUA scripting language with some mysql arguments.

-----

|pypi| |unix_build| |windows_build| |coverage| |gitter|

-----


=============
Main Conceps
=============

* Analyse and scrap third party datapacks for new userful content
* Update the scripts making them compatible with latest version of Forgotten Server


============
Installation
============


On **Windows**, just extract all contents, change variables on **config.lua** to match your MYSQL settings, import MYSQL database (*.sql) and run the provided binary.

 - Unpack global.rar to same folder:

    > capernia-ots-datapack\data\world\global.rar

 - Edit config.lua settings:

	```lua
	mysqlHost = "127.0.0.1" 
	mysqlUser = "root"
	mysqlPass = "az88231015"
	mysqlDatabase = "servidor"
	```

 - Have fun!

===========
Github Limitations
===========

Because the size limitations of Github, the following file had to be compressed.

.. code-block:: bash

    capernia-ots-datapack\data\world\global.rar


=============
Datapacks Merges
=============

This list shows the status of third party datapacks migrations:

| Name | Last Release | Capernia Status | Location |
| --- | --- |
| Mitisuig | 13/04/2016 | Debug errors | [TK](http://www.tibiaking.com/forum/topic/36403-global-full-tibiaking-10911092-tfs-12-full-oramond-cast-system-lions-rock-reward-system-equip-hotkey-new-items-news-monster-new-areas-krailos-asura-medusa-town-etc-eventos-sem-missao-v20/) |
| Absolute | 03/05/2016 | Aware of this project | [TK](http://www.tibiaking.com/forum/topic/67075-global-full-download-1090-tfs-12ferumbras-questkrailosnew-arenacastrewardeventscasino/) |


----------


