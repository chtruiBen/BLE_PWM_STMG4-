# BLE_PWM_STMG4

## Motor control schematic:
- Motor control by STM32G4 MCU when PC send the message to STM32G4 MCU through BLE
![control_sys](https://github.com/chtruiBen/BLE_PWM_STMG4-/assets/25215577/fdfa0dde-defb-4d60-a80b-056849acbd65)

### Syncronize control 
- Use TIM2 control TIM1 and TIM8 to syncronize two motors 
![sync_motor](https://github.com/chtruiBen/BLE_PWM_STMG4-/assets/25215577/467b8ace-80fe-408a-a4c7-7c44c5540f36)
  - reference (AN4776/CH.6/Fig.36)
  - https://www.st.com/resource/en/application_note/an4776-generalpurpose-timer-cookbook-for-stm32-microcontrollers-stmicroelectronics.pdf
  
