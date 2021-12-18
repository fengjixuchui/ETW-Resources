Provider                   |  Level        |  Event ID    |  Version  |  Channel  |  Task                       |  Opcode  |  Keyword                              |  Message
---------------------------|---------------|--------------|-----------|-----------|-----------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Microsoft-Windows-Wininit  |  Information  |  1           |  0        |           |  WaitForWinstationShutdown  |  Start   |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  2           |  0        |           |  WaitForWinstationShutdown  |  Stop    |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  3           |  0        |           |  PreShutdownNotification    |  Start   |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  4           |  0        |           |  PreShutdownNotification    |  Stop    |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  5           |  0        |           |  WaitForSystemProcesses     |  Start   |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  6           |  0        |           |  WaitForSystemProcesses     |  Stop    |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  7           |  0        |           |  ShutdownSystemRestore      |  Start   |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  8           |  0        |           |  ShutdownSystemRestore      |  Stop    |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  9           |  0        |           |  ShutdownWindows            |  Start   |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  10          |  0        |           |  ShutdownWindows            |  Stop    |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Warning      |  11          |  0        |  System   |                             |          |                                       |  Custom dynamic link libraries are being loaded for every application. The system administrator should review the list of libraries to ensure they are related to trusted applications. Please visit http://support.microsoft.com/kb/197571 for more information.
Microsoft-Windows-Wininit  |  Information  |  12          |  0        |  System   |                             |          |                                       |  LSASS.exe was started as a protected process with level: {Level}.
Microsoft-Windows-Wininit  |  Information  |  13          |  0        |  System   |                             |          |                                       |
Microsoft-Windows-Wininit  |  Information  |  14          |  0        |  System   |                             |          |                                       |  Credential Guard configuration: {Config}; {IsTestConfig}
Microsoft-Windows-Wininit  |  Warning      |  15          |  0        |  System   |                             |          |                                       |
Microsoft-Windows-Wininit  |  Error        |  16          |  0        |  System   |                             |          |                                       |  LsaIso.exe; the host process for Credential Guard and Key Guard; failed to launch: {Level}
Microsoft-Windows-Wininit  |  Error        |  17          |  0        |  System   |                             |          |                                       |  Error reading Credential Guard (LsaIso.exe) UEFI configuration: {Level}
Microsoft-Windows-Wininit  |  Information  |  18          |  0        |  System   |                             |          |                                       |
Microsoft-Windows-Wininit  |  Information  |  51          |  0        |           |  NtShutdownSystem           |          |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  53          |  0        |           |  SentLogoffRequest          |          |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |  Information  |  55          |  0        |           |  ReceivedShutdownRequest    |          |  PerfInstrumentation                  |
Microsoft-Windows-Wininit  |               |  1073742825  |  0        |           |                             |          |                                       |
Microsoft-Windows-Wininit  |               |  3221226487  |  0        |           |                             |          |                                       |
Microsoft-Windows-Wininit  |               |  3221228474  |  0        |           |                             |          |                                       |
Microsoft-Windows-Wininit  |               |  2147486651  |  0        |           |                             |          |                                       |
Microsoft-Windows-Wininit  |               |  2147486652  |  0        |           |                             |          |                                       |
Microsoft-Windows-Wininit  |               |  3221228477  |  0        |           |                             |          |                                       |
Microsoft-Windows-Wininit  |               |  3221228478  |  0        |           |                             |          |                                       |
Microsoft-Windows-Wininit  |  Information  |  6001        |  0        |           |  ShutdownDiagnostics        |  Start   |  PerfInstrumentation PerfDiagnostics  |
Microsoft-Windows-Wininit  |  Information  |  6002        |  1        |           |  PerfTrackFullShutdown      |          |  PerfInstrumentation                  |