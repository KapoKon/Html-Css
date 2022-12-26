# Html-Css
mat_phong 0 //graphics settings
tf_use_min_viewmodels 1
fov_desired 90
viewmodel_fov 80
hud_combattext 1

cl_interp 0.0325 //lerp
cl_interp_ratio 1
rate 97000
cl_updaterate 66
cl_cmdrate 66

hud_fastswitch "1"; //hudstuff
hud_combattext "1";
hud_combattext_batching "1";
hud_combattext_batching_window "2";
hud_medicautocallers "1";
hud_medichealtargetmarker "1";
tf_dingalingaling "1";

alias mel "slot3; alias qswitch prim" //weaponswitch
alias sec "slot2; alias qswitch prim"
alias prim "slot1; alias qswitch sec"
bind q qswitch
bind 1 prim
bind 2 sec
bind f mel

alias +mfwd "-back;+forward;alias checkfwd +forward" //stops the user from trying to move both left and right at the same time
alias +mback "-forward;+back;alias checkback +back"
alias +mleft "-moveright;+moveleft;alias checkleft +moveleft"
alias +mright "-moveleft;+moveright;alias checkright +moveright"
alias -mfwd "-forward;checkback;alias checkfwd none"
alias -mback "-back;checkfwd;alias checkback none"
alias -mleft "-moveleft;checkright;alias checkleft none"
alias -mright "-moveright;checkleft;alias checkright none"
alias checkfwd none
alias checkback none
alias checkleft none
alias checkright none
alias none ""
bind w +mfwd
bind s +mback
bind a +mleft
bind d +mright

mat_shadowstate 0 //maxfps
r_shadowmaxrendered 0
r_shadowrendertotexture 0
r_shadows 0

cl_ragdoll_fade_time 0
cl_ragdoll_forcefade 1
cl_ragdoll_physics_enable 0
g_ragdoll_fadespeed 0
g_ragdoll_lvfadespeed 0
ragdoll_sleepaftertime 0

cl_phys_props_enable 0
cl_phys_props_max 0
props_break_max_pieces 0
r_propsmaxdist 1
violence_agibs 0
violence_hgibs 0

bind \ kill //kys
bind | explode
bind 3 slot 3
bind v +inspect
