firmware.bin - прошивка под боуден limited plus v2
Актуальна на 08.03.21

Изменения:
Название файла      Строчка, которая была изменена
Configuration.h		PID_FUNCTIONAL_RANGE 20

Configuration_adv.h	#define THERMAL_PROTECTION_PERIOD 60
			#define THERMAL_PROTECTION_HYSTERESIS 5

Значения PID Хотенда:
M301 P11.37 I0.7 D46.1

P11.37
I0.7
D46.1

Отклонения:
При заданной температуре: 210*С
Отклонения при нагреве: +3*С, -3*С
При включенном на 100% обдуве:
	Опускается: 203*С
	Поднимается: 210*С