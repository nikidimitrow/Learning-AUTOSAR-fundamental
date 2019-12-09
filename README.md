#define ECUM_CODE

FUNC(void, ECUM_CODE) EcuM_Init(void);

FUNC(void, ECUM_CODE) EcuM_Shutdown(void);

FUNC(Std_ReturnType, ECUM_CODE) EcuM_SelectShutdownTarget(VAR(EcuM_StateType, AUTOMATIC) targetState, VAR(EcuM_ModeType, AUTOMATIC) resetSleepMode);
