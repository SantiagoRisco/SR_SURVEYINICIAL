# Exp_SantiagoRisco
experimento lab up

```python
SESSION_CONFIG_DEFAULTS = { 'participation_fee': 5.00 , 
'participation_fee': config_leex_1.participation_fee ,
'doc': "", 
'mturk_hit_settings': mturk_hit_settings, }
```


# self.session.config['Params']




```python
SESSION_CONFIGS = [{ 'name': 'tesis_sr', 
'real_world_currency_per_point': 0.10, 
'display_name': "Sesión Tesis Santiago Risco", 
'num_demo_participants': 16, 
'app_sequence': ['prisoner_sr', 'payment_info','demographics_sr'], }]
```




# config_leex_1.py

```python
# CONFIG PARAMETERS LEEX EXPERIMENTS SET 2017


#import random
from django import forms
# Prelims
paid_game_display = {
    'prisoner_sr': 'Bloque 1',
    'base_tesis': 'Bloque 2',
}



# GAME PARAMETERS


# GAME ORDER. Change every session!


app_sequence = ['prisoner_sr', 'demographics_sr', 'base_tesis']
#
# participation_fee (soles)
participation_fee = 10

# # Parámetros Tesis SR
PDsr_number_rounds = 15
PDsr_payment_round = 3
PDsr_ronda_preg = 14


# # Parámetros Tesis KyS
KS_lanz_pagado_ronda1 = 10
KS_lanz_pagado_ronda2 = 1


# paid_game in ['ultimatum', 'public_goods', 'trust', 'guess_two_thirds']
paid_game = 'prisoner_sr'
paid_round = 14




##################################################################################
# Order Record

# Setp 6 at 1pm:

# ['ultimatum', 'public_goods', 'trust', 'guess_two_thirds', 'payment_info', 'demographics_sr']
# paid: PG, t=2


# Setp 6 at 5pm:

# ['public_goods', 'trust', 'ultimatum', 'guess_two_thirds', 'payment_info', 'demographics_sr']
# paid: UG, t=5





##################################################################################

## TESTING PARAMS  GAME PARAMETERS

# GAME ORDER. Change every session!
#app_sequence = [ 'ultimatum', 'trust',  'payment_info', 'demographics_sr']
#
# participation_fee (soles)
# participation_fee = 10

#num_testing_rounds = 2


# ultimatum game  params
#UG_number_rounds = num_testing_rounds
#UG_endowment = 20

# public goods params
#PG_number_rounds = num_testing_rounds
#PG_endowment = 8

# trust game
#TG_number_rounds = num_testing_rounds
#TG_endowment = 8

# guessing game
#BC_number_rounds = num_testing_rounds
#BC_jackpot = 20

# # paid_game must live in ['ultimatum', 'public_goods', 'trust', 'guess_two_thirds']
#paid_game = 'ultimatum'
#paid_round = 2
```
