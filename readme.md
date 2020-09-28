This package wraps Photon 2 PUN (+Voice) into a Unity Package so it can be used as a dependency rather than stored in a Unity project.
Get the originals here:
- https://assetstore.unity.com/packages/tools/network/pun-2-free-119922
- https://assetstore.unity.com/packages/tools/audio/photon-voice-2-130518

Demo files are removed, but not other files are changed. Because of this, some minor shims are needed to have the package work correctly. In your assets folder, set up the following:

Assets\Photon
---- Resources
-------- PhotonServerSettings.asset (copied from this package, Photon\PhotonUnityNetworking\Resources)
---- Editor
-------- PunSceneSettings.asset (copied from this package, Photon\PhotonUnityNetworking\Code\Editor)
-------- PunSceneSettings.cs (blank .cs file, used by Photon to locate SceneSettings.asset in the same directory)