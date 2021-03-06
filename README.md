# rmp-cast-receiver

[Radiant Media Player](https://www.radiantmediaplayer.com) custom [Cast Application Framework](https://developers.google.com/cast/docs/caf_receiver_overview) (CAF) Receiver app

## Examples
- player.html: our production CAF custom receiver app
- player-ads.html: example for using pre-roll ads in a custom CAF receiver app
- player-drm.html: example for using DASH Widevine DRM in a custom CAF receiver app

Our production custom CAF receiver app (this is default in Radiant Media Player for version 4.7.0+) should cover most generic case-scenario. 
However you should consider developing your own custom CAF receiver app in the following cases:
- you need video ads support: [client-side ad stitching](https://developers.google.com/cast/docs/caf_receiver_features#client-side-ad-stitching) is shown in the example above. Currently this is not VAST compatible (either through IMA or rmp-vast).
- you need to support DRM: the DRM example above has been tested for DASH with Widevine DRM
- you need to apply your [own styling](https://developers.google.com/cast/docs/caf_receiver_features#styling-the-player) to the CAF player
- you need to implement some other kind of custom behaviour required by your project

Examples above are provided as starting points for Radiant Media Player users to develop a custom CAF Receiver app.
Please refer to Google docs [add Features to your CAF Receiver](https://developers.google.com/cast/docs/caf_receiver_features) for further documentation on building a custom CAF receiver app.

## Usage
Information on how use and develop a custom CAF receiver app [can be found here](https://github.com/googlecast/BasicReceiverCAF).

## Issues
Issues should be submitted in this GitHub page. We will do our best to review them.

## License
rmp-cast-receiver examples are released under Apache License 2.0.

Radiant Media Player is a commercial HTML5 video player and has its own license which can be found here: [https://www.radiantmediaplayer.com/terms-of-service.html](https://www.radiantmediaplayer.com/terms-of-service.html)
