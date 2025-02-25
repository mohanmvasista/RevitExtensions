# Release 2024.0.0

Revit 2024 support

# Release 2023.1.9

ElementExtensions:

- Method chain support

ElementIdExtensions:

- Fixed cast operations. Directly cast used by default (safe cast early)

SchemaExtensions:

- SaveEntity now return bool if the entity save was successful

SystemExtensions:

- AppendPath overload with params

# Release 2023.1.8

UnitExtensions:

- New FromUnit extension
- New ToUnit extension

# Release 2023.1.7

RibbonExtensions:

- New SetAvailabilityController() extension

ParameterExtensions:

- New Set(bool) extension
- New Set(color) extension

Nuget symbol server support: https://symbols.nuget.org/download/symbols

# Release 2023.1.6

CollectorExtensions:

- New GetElements(ElementId viewId) extension
- New GetElements(ICollection<ElementId> elementIds) extension
- New overloads for instances with ViewId

# Release 2023.1.5

New Parameter extensions

Fixed GetParameter extensions for cases where the parameter value was not initialized

# Release 2023.1.4

New Application extensions
New Collector extensions

Updated TargetFramework. It now matches the framework that Revit is running on

# Release 2023.1.3

New Schema extensions

# Release 2023.1.2

Geometry extensions

- New line.SetCoordinateX extension
- New line.SetCoordinateY extension
- New line.SetCoordinateZ extension
- New arc.SetCoordinateX extension
- New arc.SetCoordinateY extension
- New arc.SetCoordinateZ extension

# Release 2023.1.1

New JoinGeometryUtils extensions

# Release 2023.1.0

- Revit 2023 support
- Update attributes

# Release 2022.0.5

Unit extensions

- New FormatUnit extensions

Solid Extensions

- New Clone extension
- New CreateTransformed extension
- New SplitVolumes extension
- New IsValidForTessellation extension
- New TessellateSolidOrShell extension
- New FindAllEdgeEndPointsAtVertex extension

Ribbon Extensions

- New AddPushButton<TCommand> extensions
- Uri changed to UriKind.RelativeOrAbsolute

# Release 2022.0.4

Element extensions

- New GetParameter(ForgeTypeId) extension
- New Cast<T>() extension
- Removed CanBeNull attribute for ToElement<T> extension

Host Extensions

- New GetBottomFaces() extension
- New GetTopFaces() extension
- New GetSideFaces() extension

# Release 2022.0.3

Element extensions

- New Copy extension
- New Mirror extension
- New Move extension
- New Rotate extension
- New CanBeMirrored extension

Label Extensions

- New ToLabel(BuiltInParameter) extension
- New ToLabel(BuiltInParameterGroup) extension
- New ToLabel(BuiltInCategory) extension
- New ToLabel(DisplayUnitType) extension
- New ToLabel(ParameterType) extension
- New ToDisciplineLabel(ForgeTypeId) extension
- New ToGroupLabel(ForgeTypeId) extension
- New ToSpecLabel(ForgeTypeId) extension
- New ToSymbolLabel(ForgeTypeId) extension
- New ToUnitLabel(ForgeTypeId) extension

# Release 2022.0.2

Ribbon extensions

- New AddSplitButton extension
- New AddRadioButtonGroup extension
- New AddComboBox extension
- New AddTextBox extension

Unit extensions

- New FromMeters extension
- New ToMeters extension
- New FromDegrees extension
- New ToDegrees extension

ElementId extensions

- New AreEquals(BuiltInParameter) extension

# Release 2022.0.1

- Connected JetBrains annotations

# Release 2022.0.0

- Initial release