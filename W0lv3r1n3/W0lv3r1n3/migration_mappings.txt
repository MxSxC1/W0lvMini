Under Migration, if you can't find something here is rough mapping:

\Documentation\ - Wolverine\Docs or Wolverine\Wolv_Doc or \WolvMini\Docs

\SharedLib\ - \Wolverine\Libraries
\Bin\ - \Wolverine\Bin or \WolvMini\Bin
\Logs\Bin - \Wolverine\Bin or Wolverine\Bin\Logbak
\Logs\ - \Wolverine\Logs or \WolvMini\Logs - Processing Logs can be found under \Wolverine\ToProcess\Logs (or similar)
\Alerts\ - Wolverine\Logs
\Reports\ - Wolverine\Logs
\ToDo\ - \Wolverine\DumpingGround
\Process\ - \Wolverine\ToProcess
\H0stFiles\ - \Wolverine\Hosts\ - Note re-name is deliberate any host files will be similarly re-named as causes issues with anti-virus scans...yes we know we can over-ride the destination, that's what we're trying to do, but not maliciously!
\pfsense\ - \software\pfsense
\pihole\ - \software\pihole - We will be migrating away from this and writing our own...
\protected\ - \software\ssh - This directory needs secured and locked down
\config\ - \Wolverine\ or \Wolverine\config
\Database\ - \Wolverine\WolvDB\