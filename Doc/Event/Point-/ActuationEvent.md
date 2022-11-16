[Index](../../index.md) > [Event](../Event.md) > [PointEvent](PointEvent.md) > [ActuationEvent](#)
# ActuationEvent

**Display name:** Actuation event<br />
**DTMI:** dtmi:org:w3id:rec:ActuationEvent;1

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|targetPoint|**en**: target point|**en**: The brick:Point(s) (e.g., brick:Commands, brick:Setpoints, or brick:Parameters) that the actuation will target/execute.|0-Infinity|[Point](../../Point/Point.md)||True|

---

## Properties

### Inherited Properties
* **[Event](../Event.md):** customTags, end, externalIds, name, start, timestamp
* **[PointEvent](PointEvent.md):** payload

---

## Target Of
### General
* [Point](../../Point/Point.md).isPointOf
* [Agent](../../Agent/Agent.md).owns
* [Space](../../Space/Space.md).isLocationOf
* [Equipment](../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../Information/Document/Document.md).documentTopic
* [Document](../../Information/Document/Document.md).url
* [EquipmentCollection](../../Collection/Equipment-.md).feeds
* [Lease](../Lease.md).leaseOf
* [PointOfInterest](../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../Collection/Portfolio.md).includes
* [ServiceObject](../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../Asset/Equipment/Meter/Meter.md).meters