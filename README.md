
## Hello, world!

![](/Screen.png) ![](/Hierarchy.png)

1. Import [**NGUI**](https://www.assetstore.unity3d.com/en/#!/content/2413) before use.

2. Download, unzip, then copy files to Unity **Assets** folder.

3. Modify NGUI **UIScrollView.cs** , add **virtual** keyword to **Press** and **RestrictWithinBounds** void like below.

	public virtual void Press (bool pressed)

	public virtual bool RestrictWithinBounds (bool instant, bool horizontal, bool vertical)
    
4. Open **TestScene** and play it!


### Make a good game :)
