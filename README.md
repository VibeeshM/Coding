@echo off
:a
echo Calculator
echo.
set /p expression= Enter expression to calculate:
set /a ans=%expression%
echo.
echo = %ans%
pause
cls
goto a
pause
