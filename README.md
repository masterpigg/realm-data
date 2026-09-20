# ⚔️ Realm Data — Public Realm Registry & Offline DuckDB Packs

Public data repository and spatial vector registry for **[Realm Cartographer](https://github.com/masterpigg/realm-cartographer)**.
Contains pre-baked, bounded `.realm.duckdb` offline spatial databases for iconic tabletop battle map locations worldwide.

## 📊 Catalog Overview

- **Curated Landmarks Baked:** 71
- **Total Structures Indexed:** 148,219
- **Total Thoroughfares & Paths:** 117,237
- **Total Compressed Footprint:** 197.08 MB
- **Master Registry Catalog:** [`registry.json`](registry.json)
- **Release Tag:** `v1.0.0`

## 🏰 Curated Offline Realms Registry

| Realm / Landmark | Region | Category | Version | Size | Buildings | Roads | Download |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| **🏭 Kennecott Copper Mill Citadel**<br><code>kennecott_mines</code> | Alaska & Arctic | Timber Mill Citadel | <code>vv1.0.0</code> | 2.0 MB | 46 | 33 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/kennecott_mines.realm.duckdb) |
| **❄️ Mendenhall Glacier Ice Caves**<br><code>mendenhall_ice_caves</code> | Alaska & Arctic | Blue Ice Grotto | <code>vv1.0.0</code> | 2.0 MB | 0 | 5 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/mendenhall_ice_caves.realm.duckdb) |
| **🏹 Utqiaġvik (Point Barrow)**<br><code>utqiagvik_barrow</code> | Alaska & Arctic | Arctic Bluffs | <code>vv1.0.0</code> | 2.3 MB | 964 | 140 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/utqiagvik_barrow.realm.duckdb) |
| **🏢 Whittier "Town Under One Roof"**<br><code>whittier_begich</code> | Alaska & Arctic | Bunker Fortress | <code>vv1.0.0</code> | 2.0 MB | 56 | 82 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/whittier_begich.realm.duckdb) |
| **🧭 Amundsen-Scott South Pole Station**<br><code>south_pole_station</code> | Antarctica | Plateau Citadel | <code>vv1.0.0</code> | 524 KB | 0 | 0 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/south_pole_station.realm.duckdb) |
| **🩸 Blood Falls & Taylor Glacier**<br><code>blood_falls</code> | Antarctica | Bleeding Glacier | <code>vv1.0.0</code> | 1.0 MB | 0 | 0 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/blood_falls.realm.duckdb) |
| **⚓ Deception Island Flooded Caldera**<br><code>deception_island</code> | Antarctica | Drowned Volcano | <code>vv1.0.0</code> | 1.3 MB | 0 | 0 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/deception_island.realm.duckdb) |
| **🚜 Halley VI Ski-Stilt Station**<br><code>halley_vi_station</code> | Antarctica | Mobile Ice Crawler | <code>vv1.0.0</code> | 524 KB | 0 | 0 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/halley_vi_station.realm.duckdb) |
| **❄️ McMurdo Station (Ross Island)**<br><code>mcmurdo_station</code> | Antarctica | Polar Outpost Hub | <code>vv1.0.0</code> | 2.0 MB | 307 | 309 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/mcmurdo_station.realm.duckdb) |
| **🌋 Mount Erebus Caldera & Fumaroles**<br><code>mount_erebus</code> | Antarctica | Volcanic Ice Chimneys | <code>vv1.0.0</code> | 1.5 MB | 0 | 0 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/mount_erebus.realm.duckdb) |
| **🏗️ Neumayer Station III Platform**<br><code>neumayer_iii_station</code> | Antarctica | Hydraulic Ice Fortress | <code>vv1.0.0</code> | 1.3 MB | 2 | 2 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/neumayer_iii_station.realm.duckdb) |
| **🛖 Scott's Terra Nova Hut**<br><code>scotts_hut</code> | Antarctica | Expedition Cache | <code>vv1.0.0</code> | 2.0 MB | 1 | 3 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/scotts_hut.realm.duckdb) |
| **🛖 Shackleton's Nimrod Hut**<br><code>shackletons_hut</code> | Antarctica | Expedition Cache | <code>vv1.0.0</code> | 1.8 MB | 1 | 1 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/shackletons_hut.realm.duckdb) |
| **📡 Alert High Arctic Station**<br><code>alert_nunavut</code> | Canada Frontier | High Arctic Sentry | <code>vv1.0.0</code> | 2.0 MB | 57 | 45 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/alert_nunavut.realm.duckdb) |
| **⛏️ Dawson City & Dredge No. 4**<br><code>dawson_city_klondike</code> | Canada Frontier | Gold Rush Boomtown | <code>vv1.0.0</code> | 2.5 MB | 344 | 111 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/dawson_city_klondike.realm.duckdb) |
| **🏰 Prince of Wales Stone Fort**<br><code>prince_of_wales_fort</code> | Canada Frontier | Coastal Stone Bastion | <code>vv1.0.0</code> | 2.3 MB | 4 | 12 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/prince_of_wales_fort.realm.duckdb) |
| **🛡️ The Diefenbunker Blast Shelter**<br><code>diefenbunker_carp</code> | Canada Frontier | Cold War Bunker | <code>vv1.0.0</code> | 2.0 MB | 408 | 175 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/diefenbunker_carp.realm.duckdb) |
| **⚓ Fort Worden Coastal Bastion**<br><code>fort_worden</code> | Cascadia | Artillery Bastion | <code>vv1.0.0</code> | 2.3 MB | 1,738 | 740 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/fort_worden.realm.duckdb) |
| **🌲 Hoh Rain Forest Canopy**<br><code>hoh_rainforest</code> | Cascadia | Ancient Canopy | <code>vv1.0.0</code> | 2.3 MB | 10 | 58 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/hoh_rainforest.realm.duckdb) |
| **❄️ Mount Rainier Fumarole Caves**<br><code>rainier_fumaroles</code> | Cascadia | Summit Ice Grotto | <code>vv1.0.0</code> | 1.0 MB | 0 | 4 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/rainier_fumaroles.realm.duckdb) |
| **🕳️ Mount St. Helens Ape Cave**<br><code>ape_cave</code> | Cascadia | Lava Tube Conduit | <code>vv1.0.0</code> | 2.3 MB | 2 | 28 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/ape_cave.realm.duckdb) |
| **🏛️ Seattle Pioneer Square Areaways**<br><code>seattle_underground</code> | Cascadia | Submerged Street | <code>vv1.0.0</code> | 3.3 MB | 1,086 | 7,732 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/seattle_underground.realm.duckdb) |
| **🌉 Chicago — Chicago River & Bascule Bridges**<br><code>chicago_river_bascule</code> | Chicago | Bascule Canyon | <code>vv1.0.0</code> | 6.5 MB | 1,985 | 9,585 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/chicago_river_bascule.realm.duckdb) |
| **🚇 Chicago — Freight Tunnels & TARP Deep Tunnel**<br><code>chicago_freight_tunnels</code> | Chicago | Subterranean Labyrinth | <code>vv1.0.0</code> | 7.0 MB | 1,913 | 10,907 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/chicago_freight_tunnels.realm.duckdb) |
| **🏛️ Chicago — Jackson Park & White City Lagoons**<br><code>chicago_jackson_park</code> | Chicago | World's Fair Lagoon | <code>vv1.0.0</code> | 3.0 MB | 1,446 | 2,407 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/chicago_jackson_park.realm.duckdb) |
| **🗿 Carnac Megalithic Menhirs**<br><code>carnac_alignments</code> | Europe | Ancient Megaliths | <code>vv1.0.0</code> | 2.3 MB | 2,598 | 850 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/carnac_alignments.realm.duckdb) |
| **⚓ Château d'If Island Fortress**<br><code>chateau_dif</code> | Europe | Island Prison | <code>vv1.0.0</code> | 1.8 MB | 44 | 84 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/chateau_dif.realm.duckdb) |
| **🕳️ Derinkuyu Underground City**<br><code>derinkuyu_underground</code> | Europe | Megadungeon | <code>vv1.0.0</code> | 2.3 MB | 3,132 | 316 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/derinkuyu_underground.realm.duckdb) |
| **🧱 Dubrovnik Old Town Walls**<br><code>dubrovnik_walls</code> | Europe | Seaside Ramparts | <code>vv1.0.0</code> | 2.0 MB | 1,660 | 1,016 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/dubrovnik_walls.realm.duckdb) |
| **⚔️ Hadrian's Wall & Vindolanda**<br><code>hadrians_wall</code> | Europe | Roman Rampart | <code>vv1.0.0</code> | 2.0 MB | 29 | 60 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/hadrians_wall.realm.duckdb) |
| **🏰 Mont-Saint-Michel**<br><code>mont_saint_michel</code> | Europe | Tidal Citadel | <code>vv1.0.0</code> | 2.5 MB | 106 | 567 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/mont_saint_michel.realm.duckdb) |
| **🛡️ Naarden Double-Moated Fort**<br><code>naarden</code> | Europe | Star Fortress | <code>vv1.0.0</code> | 3.5 MB | 7,335 | 1,295 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/naarden.realm.duckdb) |
| **⭐ Palmanova Star Fortress**<br><code>palmanova</code> | Europe | Star Fortress | <code>vv1.0.0</code> | 1.8 MB | 1,529 | 672 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/palmanova.realm.duckdb) |
| **💀 Paris Catacombs (Ossuary)**<br><code>paris_catacombs</code> | Europe | Megadungeon | <code>vv1.0.0</code> | 7.0 MB | 8,430 | 8,716 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/paris_catacombs.realm.duckdb) |
| **💎 Wieliczka Salt Mine**<br><code>wieliczka_salt_mine</code> | Europe | Megadungeon | <code>vv1.0.0</code> | 2.8 MB | 4,443 | 4,209 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/wieliczka_salt_mine.realm.duckdb) |
| **🌊 Škocjan Caves & Karst Chasm**<br><code>skocjan_caves</code> | Europe | Karst Canyon | <code>vv1.0.0</code> | 3.0 MB | 216 | 274 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/skocjan_caves.realm.duckdb) |
| **🌋 Kazumura Basalt Lava Tube**<br><code>kazumura_cave</code> | Hawaii | Basalt Conduit | <code>vv1.0.0</code> | 1.0 MB | 369 | 32 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/kazumura_cave.realm.duckdb) |
| **🔥 Kīlauea Halemaʻumaʻu Crater**<br><code>kilauea_caldera</code> | Hawaii | Magma Caldera | <code>vv1.0.0</code> | 1.3 MB | 0 | 4 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/kilauea_caldera.realm.duckdb) |
| **🌊 Molokini Sunken Crater**<br><code>molokini_crater</code> | Hawaii | Marine Sanctuary | <code>vv1.0.0</code> | 780 KB | 0 | 0 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/molokini_crater.realm.duckdb) |
| **⛩️ Puʻuhonua o Hōnaunau Heiau**<br><code>puuhonua_o_honaunau</code> | Hawaii | Sacred Temple | <code>vv1.0.0</code> | 2.0 MB | 18 | 38 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/puuhonua_o_honaunau.realm.duckdb) |
| **🌱 Waipiʻo Valley Ahupuaʻa**<br><code>waipio_valley</code> | Hawaii | Taro Watershed | <code>vv1.0.0</code> | 2.3 MB | 93 | 40 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/waipio_valley.realm.duckdb) |
| **⚒️ Pyramiden Ghost Mining Town**<br><code>pyramiden_ghost_town</code> | High Arctic | Ghost Town Citadel | <code>vv1.0.0</code> | 2.3 MB | 75 | 189 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/pyramiden_ghost_town.realm.duckdb) |
| **🌱 Svalbard Global Seed Vault**<br><code>svalbard_seed_vault</code> | High Arctic | Doomsday Vault | <code>vv1.0.0</code> | 1.8 MB | 45 | 44 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/svalbard_seed_vault.realm.duckdb) |
| **⛩️ Fushimi Inari Torii Corridor**<br><code>fushimi_inari</code> | Japan Feudal | Shinto Shrine | <code>vv1.0.0</code> | 4.0 MB | 12,761 | 2,436 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/fushimi_inari.realm.duckdb) |
| **🏯 Himeji Castle (White Heron)**<br><code>himeji_castle</code> | Japan Feudal | Feudal Castle | <code>vv1.0.0</code> | 3.0 MB | 9,134 | 2,155 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/himeji_castle.realm.duckdb) |
| **🌲 Kumano Kodo Daimon-zaka**<br><code>kumano_kodo</code> | Japan Feudal | Pilgrim Trail | <code>vv1.0.0</code> | 2.3 MB | 162 | 212 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/kumano_kodo.realm.duckdb) |
| **♨️ Kusatsu Onsen Yubatake**<br><code>kusatsu_onsen</code> | Japan Feudal | Geothermal Spring | <code>vv1.0.0</code> | 2.5 MB | 2,490 | 780 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/kusatsu_onsen.realm.duckdb) |
| **❄️ Mount Fuji Narusawa Ice Cave**<br><code>narusawa_ice_cave</code> | Japan Feudal | Volcanic Ice Cave | <code>vv1.0.0</code> | 1.5 MB | 4 | 43 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/narusawa_ice_cave.realm.duckdb) |
| **🔭 LA — Griffith Observatory & Bronson Caves**<br><code>la_griffith_observatory</code> | Los Angeles | Mountain Overlook | <code>vv1.0.0</code> | 3.3 MB | 2,253 | 1,004 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/la_griffith_observatory.realm.duckdb) |
| **🌉 LA — Los Angeles River & 6th St Viaduct**<br><code>la_river_viaducts</code> | Los Angeles | Concrete Arroyo | <code>vv1.0.0</code> | 3.8 MB | 2,735 | 2,991 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/la_river_viaducts.realm.duckdb) |
| **🌊 LA — Sunken City Ruins & Fort MacArthur**<br><code>la_sunken_city</code> | Los Angeles | Sunken Coastal Ruins | <code>vv1.0.0</code> | 2.3 MB | 2,806 | 440 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/la_sunken_city.realm.duckdb) |
| **⚙️ Alley Spring Crimson Mill**<br><code>alley_mill_mo</code> | Missouri | Historic Gristmill | <code>vv1.0.0</code> | 2.3 MB | 16 | 64 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/alley_mill_mo.realm.duckdb) |
| **⛲ Big Spring (Elemental Surge)**<br><code>big_spring_mo</code> | Missouri | Karst Spring | <code>vv1.0.0</code> | 2.0 MB | 9 | 66 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/big_spring_mo.realm.duckdb) |
| **⚔️ Fort Davidson Star Fort**<br><code>fort_davidson_mo</code> | Missouri | Star Fort Redoubt | <code>vv1.0.0</code> | 2.0 MB | 16 | 92 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/fort_davidson_mo.realm.duckdb) |
| **🏛️ Kansas City SubTropolis**<br><code>subtropolis_kc</code> | Missouri | Limestone City | <code>vv1.0.0</code> | 2.3 MB | 102 | 434 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/subtropolis_kc.realm.duckdb) |
| **🦬 Lone Elk Wildlife Preserve**<br><code>lone_elk_preserve</code> | Missouri | Wild Game Preserve | <code>vv1.0.0</code> | 2.5 MB | 15 | 145 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/lone_elk_preserve.realm.duckdb) |
| **⛰️ Monks Mound (Cahokia)**<br><code>monks_mound_cahokia</code> | Missouri | Platform Earthwork | <code>vv1.0.0</code> | 2.0 MB | 15 | 149 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/monks_mound_cahokia.realm.duckdb) |
| **🦅 World Bird Sanctuary Aerie**<br><code>world_bird_sanctuary</code> | Missouri | Raptor Sanctuary | <code>vv1.0.0</code> | 2.5 MB | 4 | 67 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/world_bird_sanctuary.realm.duckdb) |
| **🏰 NYC — Central Park & Belvedere Castle**<br><code>central_park_belvedere</code> | New York City | Stone Folly & Park | <code>vv1.0.0</code> | 6.3 MB | 4,913 | 4,378 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/central_park_belvedere.realm.duckdb) |
| **🚇 NYC — City Hall Loop Subterranean Station**<br><code>nyc_city_hall_loop</code> | New York City | Guastavino Vault | <code>vv1.0.0</code> | 6.8 MB | 4,137 | 10,798 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/nyc_city_hall_loop.realm.duckdb) |
| **🛡️ NYC — Governors Island & Castle Williams**<br><code>governors_island_castle</code> | New York City | Coastal Star Fort | <code>vv1.0.0</code> | 4.5 MB | 709 | 2,056 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/governors_island_castle.realm.duckdb) |
| **🌿 NYC — High Line Viaduct & Sky Meadow**<br><code>nyc_high_line</code> | New York City | Elevated Rail Garden | <code>vv1.0.0</code> | 3.8 MB | 3,555 | 3,849 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/nyc_high_line.realm.duckdb) |
| **🏯 Edo Castle Moats & Ramparts**<br><code>tokyo_edo_castle</code> | Tokyo | Megalithic Walls | <code>vv1.0.0</code> | 5.0 MB | 3,115 | 4,349 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/tokyo_edo_castle.realm.duckdb) |
| **🏛️ G-Cans Storm Surge Cathedral**<br><code>tokyo_gcans</code> | Tokyo | Subterranean Tank | <code>vv1.0.0</code> | 2.5 MB | 3,021 | 645 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/tokyo_gcans.realm.duckdb) |
| **🌀 Kanda Kan-nana Diversion**<br><code>tokyo_kanda</code> | Tokyo | Flood Conduit | <code>vv1.0.0</code> | 5.5 MB | 26,509 | 4,069 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/tokyo_kanda.realm.duckdb) |
| **⚓ Odaiba Daiba Fortress Island**<br><code>tokyo_daiba</code> | Tokyo | Offshore Battery | <code>vv1.0.0</code> | 2.0 MB | 176 | 1,109 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/tokyo_daiba.realm.duckdb) |
| **🚇 Shinjuku Metro Labyrinth**<br><code>tokyo_shinjuku</code> | Tokyo | Underground Concourse | <code>vv1.0.0</code> | 6.5 MB | 11,688 | 5,733 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/tokyo_shinjuku.realm.duckdb) |
| **⚔️ DC — Fort Stevens Civil War Defenses**<br><code>dc_fort_stevens</code> | Washington DC | Civil War Redoubt | <code>vv1.0.0</code> | 4.0 MB | 8,185 | 3,420 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/dc_fort_stevens.realm.duckdb) |
| **🏛️ DC — National Mall & Lincoln Reflecting Pool**<br><code>dc_national_mall</code> | Washington DC | Monumental Axis | <code>vv1.0.0</code> | 4.3 MB | 455 | 2,975 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/dc_national_mall.realm.duckdb) |
| **🌲 DC — Theodore Roosevelt Island & Rock Creek**<br><code>dc_roosevelt_island</code> | Washington DC | Potomac Sanctuary | <code>vv1.0.0</code> | 4.5 MB | 2,434 | 4,848 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/dc_roosevelt_island.realm.duckdb) |
| **🏛️ DC — US Capitol & Congressional Tunnels**<br><code>dc_capitol_complex</code> | Washington DC | Legislative Citadel | <code>vv1.0.0</code> | 4.5 MB | 6,308 | 7,145 | [📦 Download](https://github.com/masterpigg/realm-data/releases/download/v1.0.0/dc_capitol_complex.realm.duckdb) |

## 📥 How to Use in Realm Cartographer

1. Open **Realm Cartographer**.
2. Navigate to the sidebar **📦 Offline Realm Packs** tab.
3. Under **🌐 Public Realm Registry**, click **🔄 Check Registry** to discover available realm packages.
4. Click **Download** next to any landmark to pull the pre-baked `.realm.duckdb` package directly into your local database.

## 🛠️ Automated Sync Pipeline

This repository is maintained and synchronized automatically by the GitHub Actions workflow in [masterpigg/realm-cartographer](https://github.com/masterpigg/realm-cartographer).
All `.realm.duckdb` artifacts are verified via SHA-256 checksums.
