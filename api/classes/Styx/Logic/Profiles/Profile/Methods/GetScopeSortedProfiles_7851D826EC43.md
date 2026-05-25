# Profile.GetScopeSortedProfiles Method

Returns all profiles (this + subprofiles recursively) sorted by nesting depth descending. Deepest subprofiles come first so the most specific level range wins in GetProfileForLevel. Matches HB 4.3.4 method_0 + smethod_0 behavior.

## Namespace
[Styx.Logic.Profiles](../../../../../../namespaces/Styx/Logic/Profiles.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public List<Profile> GetScopeSortedProfiles()
```

## Return Value

Type: List<Profile>
The result of the operation.

## See Also
[Profile Class](../../Profile.md)
[Styx.Logic.Profiles Namespace](../../../../../../namespaces/Styx/Logic/Profiles.md)
