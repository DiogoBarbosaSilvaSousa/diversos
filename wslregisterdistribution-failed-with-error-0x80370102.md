https://www.partitionwizard.com/partitionmagic/wslregisterdistribution-failed-with-error-0x80370102.html

Set-VMProcessor Windows_10_64_bit_Work -ExposeVirtualizationExtensions $true
Set-VMProcessor Windows_10_64_bit_Work -HwThreadCountPerCore 0
Set-VMProcessor Windows_10_64_bit -ExposeVirtualizationExtensions $true
Set-VMProcessor Windows_10_64_bit -HwThreadCountPerCore 0