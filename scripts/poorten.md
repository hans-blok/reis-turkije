C:\Users\Hans1\AppData\Local\Programs\Python\Python312\python.exe "C:\Users\Hans1\AppData\Local\Programs\Python\Python312\Scripts\mkdocs.exe" serve

Get-NetTCPConnection -LocalPort 8000 | Select-Object LocalAddress, LocalPort, State, @{Name='PID';Expression={$_.OwningProcess}}

$pid = (Get-NetTCPConnection -LocalPort 8000 -ErrorAction SilentlyContinue | Select-Object -First 1).OwningProcess
if ($pid) { Stop-Process -Id $pid -Force }

taskkill /PID 7860 /F