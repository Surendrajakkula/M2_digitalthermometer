HIGH LEVEL TEST PLAN


| Test ID | Description | Expected Input| Expected Output|Test case
| --- | --- | --- | ---- |-----|
| T_01 | LCD Message Diplay|switch on| surendra  |Pass|
| T_02| Universal Asynchronous Receiver Transmitter(USART) communication| data  | data |Pass|
| T_03 | Pulse With Modulation in sensor |in static|  successfully added |Pass|
| T_04| Voltage changes |5v|98.6 F (37 C)|Pass|


LOW LEVEL TEST PLAN


| Test ID | Description | I/P|  O/P|
| --- | --- | --- | ---- |
| L_01 |  When switch is close | switch closed | No LCD Displays |
| L_02| When Potentiometer is set at 0|0v |0 temperature|
| L_02| When Voltage is set at 0|0v |0 temperature|
