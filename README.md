# BedrockData
Data generated from BDS. 

## 1. block_attributes

Block attributes extracted from BDS.

Contains aabb, hardness, resistance, friction ... for each ```block state```.

## 2. item_data
format: big endian gzip compression  
Item data extracted from BDS.

## 3. block_palette
format: big endian gzip compression  
Block palette table extracted from BDS. 

Similar to https://github.com/CloudburstMC/Data/blob/master/block_palette.nbt

## 4. biome_definitions
format: big endian gzip compression  
Biome definitions extracted from BDS.

## 5. available_commands_packet

AvailableCommandsPacket bin extracted from BDS.

## 6. command_xxx

Command related data extracted from BDS.

## 7. entity_data

Entity type (and few data) extracted from BDS.

## 8. block_property_types

All the vanilla block property type extracted from BDS. Including the value type, serialization name etc...

## 9. biome_id_and_type

Vanilla biomes' name & id & type

## 10. creative_items
format: big endian gzip compression  
Creative player's inventory dumping from BDS

## 11. block_id_to_item_id_map

Including all the vanilla hard-coded block <-> block-item pair

## 12. recipes

Vanilla recipes extracted from BDS

## 13. block materials

## 14. block_correct_tool_special

### Want to generate these files by yourself?

You can use this tool [DataExtractor](https://github.com/AllayMC/DataExtractor)
