---
-api-id: M:Windows.Services.Maps.OfflineMaps.OfflineMapPackage.FindPackagesInGeocircleAsync(Windows.Devices.Geolocation.Geocircle)
-api-type: winrt method
---

<!-- Method syntax.
public IAsyncOperation<OfflineMapPackageQueryResult> OfflineMapPackage.FindPackagesInGeocircleAsync(Geocircle queryCircle)
-->

# Windows.Services.Maps.OfflineMaps.OfflineMapPackage.FindPackagesInGeocircleAsync


## -description

Starts an asynchronous operation to find a map package that contains map data for specified geographic area.

## -parameters

### -param queryCircle

The geographic area that defines the area that you want to locate a map package for.

## -returns

An [OfflineMapPackageQueryResult](offlinemappackagequeryresult.md) that contains the result of the query.

## -remarks

This query can find multiple matches. It can also find no matches at all (For example: if you specify a border region or an area in the middle of the ocean).

## -see-also

## -examples

