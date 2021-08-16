# unity-plugin

## Integrating into your Unity project

1. Download the Pubguard.unitypackage file from https://github.com/bidstack-group/pubguard-unity-plugin/Pubguard.unitypackage
2. In your Unity project, go to Assets → Import Package → Custom Package, select Pubguard.unitypackage. Keep all the files in the Importing Package window selected, and click Import.
3. (only for Android) Resolve dependencies by going to Assets → External Dependency Manager → Android Resolver → Resolve
4. In your main scene, add a new empty Object, rename it to PubguardController.
5. With the PubguardController selected, go to component → add → Pubguard.
6. Leave the customer key field empty for now, it's not required yet.

