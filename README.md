# BitTorrent
The parallel piece system is analogous to the centralized directory mechanism, as each peer needs to communicate to the tracker which pieces it makes available and periodically update their status. Each peer can make new files available, but it is required to make available all the pieces of the files it has requested.

The download is performed by requesting multiple pieces in parallel from different peers. The receiving peer selects the peers to use for the download based on up-to-date information about the pieces owned by each peer. The selection mechanism prioritizes the least available pieces and, among peers with the same priority, makes a random selection.

Peers periodically provide the tracker with an updated status of the pieces they possess and request the current status of the pieces belonging to the files they are downloading.

### Running 

```
 cd ../BitTorrent
 python3 main.py
```


## Authors :trollface:

* **ArtPes** - (https://github.com/ArtPes)
* **lovalova91** - (https://github.com/lovalova1991)
* **padovanl** - (https://github.com/padovanl)
* **lucia-rignanese** - (https://github.com/lucia-rignanese)

See also the list of [contributors](https://github.com/ArtPes/BitTorrent/graphs/contributors) who participated in this project.
