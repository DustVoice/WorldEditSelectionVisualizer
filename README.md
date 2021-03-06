# WorldEditSelectionVisualizer
[![Build Status](https://travis-ci.org/MrMicky-FR/WorldEditSelectionVisualizer.svg?branch=master)](https://travis-ci.org/MrMicky-FR/WorldEditSelectionVisualizer) 
[![codecov](https://codecov.io/gh/MrMicky-FR/WorldEditSelectionVisualizer/branch/master/graph/badge.svg)](https://codecov.io/gh/MrMicky-FR/WorldEditSelectionVisualizer)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a9fd5bd3cfa3443cac965a7c89ebbccb)](https://www.codacy.com/app/MrMicky-FR/WorldEditSelectionVisualizer?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=MrMicky-FR/WorldEditSelectionVisualizer&amp;utm_campaign=Badge_Grade) 
[![Maintenance](https://img.shields.io/maintenance/yes/2018.svg)]()

WorldEditSelectionVisualizer (WESV) is essentially the famous [WorldEditCUI](http://www.minecraftforum.net/topic/2171206-172-worldeditcui/) mod in the form of a bukkit plugin, which means that players don't need to install anything on their client.

## Features

- Spawns particles around WorldEdit selections so players can see them
- No client mod required
- Supports cuboid, sphere, ellipsoid, cylinder, polygon and convex selections
- Use `/wesv` to toggle the visualizer
- Only show the selection when holding the selection item
- Configurable particle effect
- Force large particle distances to see your selection from far away
- Prevent players from spawning too many particles when selecting huge regions
- Highly customizable for the performance of your server

## Downloads

You can download releases and find more information on SpigotMC: https://www.spigotmc.org/resources/worldeditselectionvisualizer.17311/

## Screenshots

![Cuboid selection](http://i.imgur.com/0MAcN3o.png)
![Polygon selection](http://i.imgur.com/OqSQQr7.png)
![Ellipsoid selection](http://i.imgur.com/pOwYY62.png)
![Customizable particle effect and particle distance](http://i.imgur.com/VcR0IMA.png)

## Metrics

WorldEditSelectionVisualizer collects statistics anonymously via [bStats](https://bstats.org/). You can see the statistics here: https://bstats.org/plugin/bukkit/WorldEditSelectionVisualizer
If you want to disable bStats, you just need to set `enabled` to `false` in `plugins/bStats/config.yml`, but statistics are really useful for developers.
