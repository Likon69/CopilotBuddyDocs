# PerformanceTimer Class

Simple performance timer for measuring execution time of code blocks. Use in a using statement or call Start()/StopAndPrint() manually.

## Inheritance Hierarchy
System.Object
  Styx.Helpers.PerformanceTimer

## Namespace
[Styx.Helpers](../../../namespaces/Styx/Helpers.md)

## Assembly
CopilotBuddy (in CopilotBuddy.dll)

## Syntax
```csharp
public class PerformanceTimer : IDisposable
```

The PerformanceTimer type exposes the following members.

## Constructors

| | Name | Description |
| --- | --- | --- |
| Public constructor | [PerformanceTimer(string)](PerformanceTimer/Constructors/Constructor_1C8BECFE87E3.md) | Creates a new performance timer with the specified debug text. |

## Properties

| | Name | Description |
| --- | --- | --- |
| Public property | [Elapsed](PerformanceTimer/Properties/Elapsed_AE213E517ABE.md) | Gets the elapsed time as a TimeSpan. |
| Public property | [ElapsedMilliseconds](PerformanceTimer/Properties/ElapsedMilliseconds_39D86BA37176.md) | Gets the elapsed time in milliseconds. |
| Public property | [ElapsedTicks](PerformanceTimer/Properties/ElapsedTicks_D509EE3584D7.md) | Gets the elapsed time in ticks. |
| Public property | [IsRunning](PerformanceTimer/Properties/IsRunning_FA48F8076E45.md) | Gets whether the timer is currently running. |

## Methods

| | Name | Description |
| --- | --- | --- |
| Public method | [Dispose](PerformanceTimer/Methods/Dispose_EA8E9AE01FBD.md) | Disposes the timer. Stops and prints if not already done. |
| Public method | [DontPrint](PerformanceTimer/Methods/DontPrint_7269355EFCA2.md) | Prevents the timer from printing when stopped or disposed. |
| Public method | [Reset](PerformanceTimer/Methods/Reset_024A33244A09.md) | Resets the timer to zero. |
| Public method | [Restart](PerformanceTimer/Methods/Restart_BDEC38C04ECC.md) | Resets and starts the timer. |
| Public method | [Start](PerformanceTimer/Methods/Start_BBE47ADCFB6F.md) | Starts or resumes the timer. |
| Public method | [StartConditional](PerformanceTimer/Methods/StartConditional_3968C1DBA830.md) | Starts the timer only in debug builds with TIMERS defined. |
| Public method Static member | [StartNew(string)](PerformanceTimer/Methods/StartNew_D9AC822508E9.md) | Creates a PerformanceTimer that automatically starts. |
| Public method | [Stop](PerformanceTimer/Methods/Stop_B9D2DB5ECD1C.md) | Stops the timer without printing. |
| Public method | [StopAndPrint](PerformanceTimer/Methods/StopAndPrint_8096DAC1D92B.md) | Stops the timer and prints the elapsed time. |
| Public method | [StopAndPrintConditional](PerformanceTimer/Methods/StopAndPrintConditional_8346772B563B.md) | Stops and prints only in debug builds with TIMERS defined. |
| Public method | Equals(object) | Determines whether the specified object is equal to the current object. (Inherited from object.) |
| Protected method | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from object.) |
| Public method | GetHashCode | Serves as a hash function for a particular type. (Inherited from object.) |
| Public method | GetType | Gets the Type of the current instance. (Inherited from object.) |
| Protected method | MemberwiseClone | Creates a shallow copy of the current Object. (Inherited from object.) |
| Public method | ToString | Returns a string that represents the current object. (Inherited from object.) |

## See Also
[Styx.Helpers Namespace](../../../namespaces/Styx/Helpers.md)
