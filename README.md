# 参考
Google Codelab Tutrial: [Create an AR game using Unity's AR Foundation](https://codelabs.developers.google.com/arcore-unity-ar-foundation#0)

ただし、上記チュートリアルは不完全な部分があるため、以下を修正する必要がある。
- `ReticleBehaviour.cs`の`Update()`関数内、`if (hits.Length)`を`if (hits.Count)`に変更する
- `DrivingSurfaceManager.cs`の`Start()`関数内、46行目の後に`RaycastManager = GetComponent<ARRaycastManager>();`を追加する