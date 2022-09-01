#### C#

**iOS syntax**

```csharp
public static void SetAdvertisingIdentifier (string adId);
```

* _adId_ _(String)_ provides developers with a simple, standard system to continue to track the Ads through their apps.

**Android syntax**

```csharp
public unsafe static void SetAdvertisingIdentifier (string advertisingIdentifier);
```

* _advertisingIdentifier_ _(String)_ provides developers with a simple, standard system to continue to track the Ads through their apps.

**Example**

```csharp
ACPCore.SetAdvertisingIdentifier("ADVTID");
```