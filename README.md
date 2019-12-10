#TODO:
1) MCAL
2) Microcontroller Abstraction Layer
3) ECU Abstraction Layer
4) Services Layer
5) Complex Drivers

#define ECUM_CODE

FUNC(void, ECUM_CODE) EcuM_Init(void);

FUNC(void, ECUM_CODE) EcuM_Shutdown(void);

FUNC(Std_ReturnType, ECUM_CODE) EcuM_SelectShutdownTarget(VAR(EcuM_StateType, AUTOMATIC) targetState, VAR(EcuM_ModeType, AUTOMATIC) resetSleepMode);
