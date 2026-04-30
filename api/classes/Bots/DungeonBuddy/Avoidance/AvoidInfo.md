# AvoidInfo Class

Définit une zone à éviter (ability de boss, feu au sol, etc.)

## Inheritance Hierarchy
System.Object
  Bots.DungeonBuddy.Avoidance.AvoidInfo

## Namespace
[Bots.DungeonBuddy.Avoidance](../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class AvoidInfo
```

The AvoidInfo type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [AvoidInfo(CanRunDecoratorDelegate, Predicate<WoWObject>, Func<float>)](AvoidInfo/Constructors/Constructor_29D5735BE24C.md) | Créer un avoid basé sur un objet |
| Public constructor | [AvoidInfo(CanRunDecoratorDelegate, Func<WoWPoint>, Func<float>)](AvoidInfo/Constructors/Constructor_D640C7CAE432.md) | Créer un avoid basé sur une position fixe |
| Public constructor | [AvoidInfo(CanRunDecoratorDelegate, Predicate<WoWObject>, Func<float>, bool)](AvoidInfo/Constructors/Constructor_E0C654A03395.md) | Initializes a new instance of the AvoidInfo class. |
| Public constructor | [AvoidInfo(CanRunDecoratorDelegate, Predicate<WoWObject>, Func<float>, Func<WoWPoint>, float, bool)](AvoidInfo/Constructors/Constructor_216080B61CD4.md) | Initializes a new instance of the AvoidInfo class. |
| Public constructor | [AvoidInfo(CanRunDecoratorDelegate, Func<WoWPoint>, Func<float>, Func<WoWPoint>, float, bool)](AvoidInfo/Constructors/Constructor_5B412A2FD7B3.md) | Initializes a new instance of the AvoidInfo class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Condition](AvoidInfo/Properties/Condition_40463EE3E3B1.md) | Condition pour activer l'avoid |
| Public property | [IsBlocking](AvoidInfo/Properties/IsBlocking_D99F80F9B1E1.md) | Si true, bloque la navigation à travers cette zone |
| Public property | [LeashPointSelector](AvoidInfo/Properties/LeashPointSelector_766805C8D306.md) | Point d'ancrage (ne pas fuir plus loin que LeashRadius de ce point) |
| Public property | [LeashRadius](AvoidInfo/Properties/LeashRadius_E07878F37E66.md) | Rayon maximum de fuite depuis le point d'ancrage |
| Public property | [LocationSelector](AvoidInfo/Properties/LocationSelector_D8AC9BA9AD6C.md) | Sélecteur de position (pour avoid statique) |
| Public property | [ObjectSelector](AvoidInfo/Properties/ObjectSelector_46F81151E375.md) | Sélecteur d'objets (pour avoid dynamique) |
| Public property | [RadiusSelector](AvoidInfo/Properties/RadiusSelector_01BCCD81EFC5.md) | Sélecteur de rayon |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CanRun(object)](AvoidInfo/Methods/CanRun_43D9AD6CBD7A.md) | Determines whether can run. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Bots.DungeonBuddy.Avoidance Namespace](../../../../namespaces/Bots/DungeonBuddy/Avoidance.md)
