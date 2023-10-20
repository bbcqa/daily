ℹ️ Repository exposing **public** links &amp; resources to the "BBC Daily" testers.

<!-- Remember that blank lines are needed before/after a section of markdown that is within an html tag, otherwise the markdown won't work -->

## IDFM Partner

#### Search on IDFM
```
blablacardaily://search
  ?departure_location=lat%3D48.803890%2Clon%3D2.126782
  &arrival_location=lat%3D48.869384%2Clon%3D2.337933
  &departure_datetime=2021-08-23T08%3A00%3A00%2B01%3A00
  &partner=NAVIGO
  &utm_campaign=FR_NAT_PARTNERS
```
- [🔗 With `blablacardaily://` scheme](blablacardaily://search?departure_location=lat%3D48.803890%2Clon%3D2.126782&arrival_location=lat%3D48.869384%2Clon%3D2.337933&departure_datetime=2021-08-23T08%3A00%3A00%2B01%3A00&partner=NAVIGO&utm_campaign=FR_NAT_PARTNERS)

## Google Maps Partner

#### Search with pickup=`my_location` & drop-off in IDF
```
// "My location" -> "Château de Versailles"
blablacardaily://book-a-ride
  ?pickup=my_location
  &dropoff_latitude=48.803890
  &dropoff_longitude=2.126782
```
- [🔗 With `blablacardaily://` scheme](blablacardaily://book-a-ride?pickup=my_location&dropoff_latitude=48.803890&dropoff_longitude=2.126782)
- [🔗 With `https://` scheme](https://open.blablacardaily.com/book-a-ride?pickup=my_location&dropoff_latitude=48.803890&dropoff_longitude=2.126782)

#### Search with pickup in IDF & drop-off=`my_location`
```
// "Château de Versailles" -> "My location"
blablacardaily://book-a-ride
  ?dropoff=my_location
  &pickup_latitude=48.803890
  &pickup_longitude=2.126782
```
- [🔗 With `blablacardaily://` scheme](blablacardaily://book-a-ride?dropoff=my_location&pickup_latitude=48.803890&pickup_longitude=2.126782)
- [🔗 With `https://` scheme](https://open.blablacardaily.com/book-a-ride?dropoff=my_location&pickup_latitude=48.803890&pickup_longitude=2.126782)

#### Search with pickup & drop-off in IDF
```
// "6, rue Saint-Sabin" -> "Château de Versailles"
blablacardaily://book-a-ride
  ?pickup_latitude=48.85504296738133
  &pickup_longitude=2.3719849244470934
  &dropoff_latitude=48.803890
  &dropoff_longitude=2.126782
```
- [🔗 With `blablacardaily://` scheme](blablacardaily://book-a-ride?pickup_latitude=48.85504296738133&pickup_longitude=2.3719849244470934&dropoff_latitude=48.803890&dropoff_longitude=2.126782)
- [🔗 With `https://` scheme](https://open.blablacardaily.com/book-a-ride?pickup_latitude=48.85504296738133&pickup_longitude=2.3719849244470934&dropoff_latitude=48.803890&dropoff_longitude=2.126782)

#### Search with pickup=`my_location` & drop-off *not* in IDF
```
// "My location" -> "Parlement de Bretagne (Rennes)"
blablacardaily://book-a-ride
  ?pickup=my_location
  &dropoff_latitude=48.11177009606368
  &dropoff_longitude=-1.6775474034472833
```
- [🔗 With `blablacardaily://` scheme](blablacardaily://book-a-ride?pickup=my_location&dropoff_latitude=48.11177009606368&dropoff_longitude=-1.6775474034472833)
- [🔗 With `https://` scheme](https://open.blablacardaily.com/book-a-ride?pickup=my_location&dropoff_latitude=48.11177009606368&dropoff_longitude=-1.6775474034472833)
