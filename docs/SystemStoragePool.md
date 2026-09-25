# SystemStoragePool


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alignment** | **int** | Optionally, configure the sector alignment size for the pool; defaults to 4096 byte sectors. Must be a power of two. Can only be specified when initially creating the pool. | [optional] 
**allow_mixed_dev_sizes** | **bool** | If true, allow creation of a pool with devices of different sizes. | [optional] 
**cache** | **List[str]** |  | [optional] 
**cache_degraded** | **List[str]** |  | [optional] 
**devices** | **List[str]** | Devices, Cache, Log, and Special can be modified to add/remove/replace devices in the pool. | [optional] 
**devices_degraded** | **List[str]** |  | [optional] 
**encryption_key_status** | **str** |  | [optional] 
**last_scrub** | [**SystemStoragePoolScrubStatus**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemStoragePoolScrubStatus.md) |  | [optional] 
**last_trim** | [**SystemStoragePoolTrimStatus**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemStoragePoolTrimStatus.md) |  | [optional] 
**log** | **List[str]** |  | [optional] 
**log_degraded** | **List[str]** |  | [optional] 
**managed** | **bool** | Read-only fields returned from the server with additional pool information. | [optional] 
**name** | **str** | Name and Type cannot be changed after pool creation. | [optional] 
**pool_allocated_space_in_bytes** | **int** |  | [optional] 
**raw_pool_size_in_bytes** | **int** |  | [optional] 
**special** | [**SystemStoragePoolSpecial**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemStoragePoolSpecial.md) |  | [optional] 
**special_degraded** | **List[str]** |  | [optional] 
**state** | **str** |  | [optional] 
**type** | **str** | Supported pool types: zfs-raid0, zfs-raid1, zfs-raid10, zfs-raidz1, zfs-raidz2, zfs-raidz3. | [optional] 
**usable_pool_size_in_bytes** | **int** |  | [optional] 
**volumes** | [**List[SystemStoragePoolVolume]**](https://github.com/anonhostpi/pyincusd/blob/v7.5.1/docs/SystemStoragePoolVolume.md) |  | [optional] 

## Example

```python
from pyincusd.models.system_storage_pool import SystemStoragePool

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStoragePool from a JSON string
system_storage_pool_instance = SystemStoragePool.from_json(json)
# print the JSON string representation of the object
print(SystemStoragePool.to_json())

# convert the object into a dict
system_storage_pool_dict = system_storage_pool_instance.to_dict()
# create an instance of SystemStoragePool from a dict
system_storage_pool_from_dict = SystemStoragePool.from_dict(system_storage_pool_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


