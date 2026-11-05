$new = Join-Path $env:GRP_INSTALL_ROOT 'lib/Legacy.dll'
if (-not (Test-Path $new)) { exit 3 }
Set-Content -Path (Join-Path $env:GRP_INSTALL_ROOT 'app/data/migrated-0.3.0.txt') -Value (Get-Content $new)