This config will populate the following:

- Charts (random, trending, popular, top-rated, most watched)
- Awards
- Year (top-rated)
- Decades (top-rated)
- Genre (popular)
- Genre (top-rated)
- Sub-genre (top-rated) *
- Holidays *
- TMBD collections *

For more details on what each section contains: [movies](MOVIES.md) | [shows](SHOWS.md)
<br/>
<br/>
<br/>
**Install:**

clone into PMM's root directory:
```
git clone https://github.com/0x5f3/pmm-config config
```
initial run to populate collections:
```
python plex_meta_manager.py --config config/movie.yml --collections-only --run --ignore-schedules
python plex_meta_manager.py --config config/show.yml --collections-only --run --ignore-schedules
```
<br/>
<br/>
After a sucessfull run, you should have something like this:

![shows]assets/_/shows.jpg)