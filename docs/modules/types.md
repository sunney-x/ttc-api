[ttc-api](../README.md) / [Modules](../modules.md) / types

# Module: types

## Table of contents

### Enumerations

- [Color](../enums/types.Color.md)
- [Mode](../enums/types.Mode.md)
- [TransportType](../enums/types.TransportType.md)

### Interfaces

- [ArrivalInfo](../interfaces/types.ArrivalInfo.md)
- [ArrivalTimesResponse](../interfaces/types.ArrivalTimesResponse.md)
- [BusLiveInfo](../interfaces/types.BusLiveInfo.md)
- [BusesResponse](../interfaces/types.BusesResponse.md)
- [Route](../interfaces/types.Route.md)
- [RouteInfo](../interfaces/types.RouteInfo.md)
- [RouteStop](../interfaces/types.RouteStop.md)
- [Stop](../interfaces/types.Stop.md)
- [StopInfo](../interfaces/types.StopInfo.md)
- [StopRoute](../interfaces/types.StopRoute.md)

### Type aliases

- [BusRoute](types.md#busroute)

## Type aliases

### BusRoute

Ƭ **BusRoute**: [`Route`](../interfaces/types.Route.md) & { `Type`: [`Bus`](../enums/types.TransportType.md#bus)  }

#### Defined in

[types.ts:23](https://github.com/sunney-x/ttc-api/blob/624d85c/src/types.ts#L23)
