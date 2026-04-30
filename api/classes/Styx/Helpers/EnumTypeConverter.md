# EnumTypeConverter Class

Value converter to support enum display names and localization. Ported from HB 4.3.4. Deobfuscated: Class442→EnumCacheEntry, Class443→CultureCacheEntry, Class444→ResourceLocalizer, Delegate5→LocalizerDelegate.

## Inheritance Hierarchy
System.Object
  System.ComponentModel.TypeConverter
    System.ComponentModel.EnumConverter
      Styx.Helpers.EnumTypeConverter

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class EnumTypeConverter : EnumConverter
```

The EnumTypeConverter type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [EnumTypeConverter(Type)](EnumTypeConverter/Constructors/Constructor_F0204A89B1F3.md) | Initializes a new instance of the EnumTypeConverter class. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Protected property | Comparer | Gets the comparer. (Inherited from EnumConverter.) |
| Protected property | EnumType | Gets the enum type. (Inherited from EnumConverter.) |
| Protected property | Values | Gets or sets the values. (Inherited from EnumConverter.) |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [CanConvertFrom(ITypeDescriptorContext, Type)](EnumTypeConverter/Methods/CanConvertFrom_CF3850A8BFE1.md) | Determines whether can convert from. (Overrides EnumConverter.CanConvertFrom().) |
| Public method | [CanConvertTo(ITypeDescriptorContext, Type)](EnumTypeConverter/Methods/CanConvertTo_29D0DD83863F.md) | Determines whether can convert to. (Overrides EnumConverter.CanConvertTo().) |
| Public method | [ConvertFrom(ITypeDescriptorContext, CultureInfo, object)](EnumTypeConverter/Methods/ConvertFrom_7802109EFC43.md) | Converts from the specified value. (Overrides EnumConverter.ConvertFrom().) |
| Public method | [ConvertTo(ITypeDescriptorContext, CultureInfo, object, Type)](EnumTypeConverter/Methods/ConvertTo_9CBA8FC257FB.md) | Converts to the specified type. (Overrides EnumConverter.ConvertTo().) |
| Public method | [GetCreateInstanceSupported(ITypeDescriptorContext)](EnumTypeConverter/Methods/GetCreateInstanceSupported_0B90DF85CD3B.md) | Gets the create instance supported. (Overrides TypeConverter.GetCreateInstanceSupported().) |
| Public method | [GetPropertiesSupported(ITypeDescriptorContext)](EnumTypeConverter/Methods/GetPropertiesSupported_352FCB897BCF.md) | Gets the properties supported. (Overrides TypeConverter.GetPropertiesSupported().) |
| Public method | [GetStandardValues(ITypeDescriptorContext)](EnumTypeConverter/Methods/GetStandardValues_E8B511B11151.md) | Gets the standard values. (Overrides EnumConverter.GetStandardValues().) |
| Public method | [GetStandardValuesExclusive(ITypeDescriptorContext)](EnumTypeConverter/Methods/GetStandardValuesExclusive_BFFC67AF8EE8.md) | Gets the standard values exclusive. (Overrides EnumConverter.GetStandardValuesExclusive().) |
| Public method | [GetStandardValuesSupported(ITypeDescriptorContext)](EnumTypeConverter/Methods/GetStandardValuesSupported_31BD1F8A24B3.md) | Gets the standard values supported. (Overrides EnumConverter.GetStandardValuesSupported().) |
| Public method | [IsValid(ITypeDescriptorContext, object)](EnumTypeConverter/Methods/IsValid_379017E330D6.md) | Determines whether is valid. (Overrides EnumConverter.IsValid().) |
| Public method Static member | [RegisterResourceManager(Type, ResourceManager)](EnumTypeConverter/Methods/RegisterResourceManager_EFEED339936A.md) | Registers a resource manager for the specified type. |
| Public method | CanConvertFrom(Type) | Determines whether can convert from. (Inherited from TypeConverter.) |
| Public method | CanConvertTo(Type) | Determines whether can convert to. (Inherited from TypeConverter.) |
| Public method | ConvertFrom(object) | Converts from the specified value. (Inherited from TypeConverter.) |
| Public method | ConvertFromInvariantString(string) | Converts from an invariant string. (Inherited from TypeConverter.) |
| Public method | ConvertFromInvariantString(ITypeDescriptorContext, string) | Converts from an invariant string. (Inherited from TypeConverter.) |
| Public method | ConvertFromString(string) | Converts from a string. (Inherited from TypeConverter.) |
| Public method | ConvertFromString(ITypeDescriptorContext, string) | Converts from a string. (Inherited from TypeConverter.) |
| Public method | ConvertFromString(ITypeDescriptorContext, CultureInfo, string) | Converts from a string. (Inherited from TypeConverter.) |
| Public method | ConvertTo(object, Type) | Converts to the specified type. (Inherited from TypeConverter.) |
| Public method | ConvertToInvariantString(object) | Converts to an invariant string. (Inherited from TypeConverter.) |
| Public method | ConvertToInvariantString(ITypeDescriptorContext, object) | Converts to an invariant string. (Inherited from TypeConverter.) |
| Public method | ConvertToString(object) | Converts to a string. (Inherited from TypeConverter.) |
| Public method | ConvertToString(ITypeDescriptorContext, object) | Converts to a string. (Inherited from TypeConverter.) |
| Public method | ConvertToString(ITypeDescriptorContext, CultureInfo, object) | Converts to a string. (Inherited from TypeConverter.) |
| Public method | CreateInstance(IDictionary) | Creates the instance. (Inherited from TypeConverter.) |
| Public method | CreateInstance(ITypeDescriptorContext, IDictionary) | Creates the instance. (Inherited from TypeConverter.) |
| Protected method | GetConvertFromException(object) | Gets the convert from exception. (Inherited from TypeConverter.) |
| Protected method | GetConvertToException(object, Type) | Gets the convert to exception. (Inherited from TypeConverter.) |
| Public method | GetCreateInstanceSupported | Gets the create instance supported. (Inherited from TypeConverter.) |
| Public method | GetProperties(object) | Gets the properties. (Inherited from TypeConverter.) |
| Public method | GetProperties(ITypeDescriptorContext, object) | Gets the properties. (Inherited from TypeConverter.) |
| Public method | GetProperties(ITypeDescriptorContext, object, Attribute[]) | Gets the properties. (Inherited from TypeConverter.) |
| Public method | GetPropertiesSupported | Gets the properties supported. (Inherited from TypeConverter.) |
| Public method | GetStandardValues | Gets the standard values. (Inherited from TypeConverter.) |
| Public method | GetStandardValuesExclusive | Gets the standard values exclusive. (Inherited from TypeConverter.) |
| Public method | GetStandardValuesSupported | Gets the standard values supported. (Inherited from TypeConverter.) |
| Public method | IsValid(object) | Determines whether is valid. (Inherited from TypeConverter.) |
| Protected method | SortProperties(PropertyDescriptorCollection, string[]) | Sorts the properties. (Inherited from TypeConverter.) |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
