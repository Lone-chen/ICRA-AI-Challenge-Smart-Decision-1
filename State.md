## Definition of State Space
#### Robot information parameter:
* BatteryPitchAngle	pitch angle of battery
* BatteryYawAngle	yaw angle of battery
* ConsoleAngle	angle of console
* Coordinate	the coordinates of robot
	
#### Game information parameter:
* HP	blood volume
* Bullet	Bullets
* BarrelTemperature	barrel heat
* SupplyDis	distance from supply
* SupplyUse	replenishment times
* DefenseDis	distance from the defense zone
* DefenseTime	remaining defense time
* DefenseStayTime	time spent in the defense zone
* DefenseUse	whether defensive bonus skills have been used
* CompetingTime	time from compete begin
* DefensiveAreaLocation	location of defensive area
* SupplyAreaLocation	location of supply area

## State parameter of the robot:
#### Self state parameter:
* HP: blood volume
* Bullet: Bullets
* Coordinate: coordinates
* BatteryAngle: Battery angle
* ConsoleAngle: console angle
* BarrelTemperature: barrel heat
* LeftTime: the remaining time of the game
* SupplyDis: distance from supply
* SupplyUse: Replenishment times
* DefenseDis: distance from the defense zone
* DefenseTime: Remaining defense time
* DefenseStayTime: Time spent in the defense zone
* DefenseUse: Whether defensive bonus skills have been used
#### Enemy state parameter:
* Good enemy vehicle  status parameters
* GoodHP：Blood volume
* GoodCoordinate：Coordinates
* GoodDis：Enemy better chariot distance
* GoodBatteryDirection：Fortress orientation
* GoodSupplyDis：Distance from supply
* GoodDefenseDis：Distance from the defense zone
* Bad enemy vehicle status parameters
* BadHP：Blood volume
* BadCoordinate：Coordinates
* BadDis：Enemy enemy chariot distance
* BadBatteryDirection：Fortress orientation
* BadSupplyDis：Distance from supply
* BadDefenseDis：Distance from the defense zone
