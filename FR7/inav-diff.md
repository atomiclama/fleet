```
diff

# version
# INAV/OMNIBUSF4V3_S5_S6_2SS 2.4.0 Apr 24 2020 / 12:42:18 (deb05302f)
# GCC-9.2.1 20191025 (release) [ARM/arm-9-branch revision 277599]

# start the command batch
batch start

# resources

# mixer
mmix 0  1.000 -0.809  1.000  1.000
mmix 1  1.000 -1.000 -1.000 -1.000
mmix 2  1.000  0.809  1.000 -1.000
mmix 3  1.000  1.000 -1.000  1.000

# servo mix

# servo

# logic

# gf

# feature
feature DYNAMIC_FILTERS
feature SOFTSERIAL
feature GPS
feature CURRENT_METER
feature PWM_OUTPUT_ENABLE

# beeper

# map

# serial
serial 0 64 115200 57600 0 115200
serial 5 2 115200 57600 0 115200
serial 30 4096 115200 115200 0 19200

# led

# color

# mode_color

# aux
aux 0 0 3 1500 2100
aux 1 1 4 1500 2100
aux 2 9 5 1500 2100
aux 3 8 2 1500 2100

# adjrange

# rxrange

# temp_sensor

# wp
#wp 0 invalid

# osd_layout
osd_layout 0 0 17 2 H
osd_layout 0 1 2 7 H
osd_layout 0 3 8 6 H
osd_layout 0 4 8 6 H
osd_layout 0 7 13 12 H
osd_layout 0 9 1 2 H
osd_layout 0 11 2 8 V
osd_layout 0 12 21 10 V
osd_layout 0 13 2 5 V
osd_layout 0 14 6 2 V
osd_layout 0 15 2 6 V
osd_layout 0 20 18 13 V
osd_layout 0 21 3 13 V
osd_layout 0 22 13 3 V
osd_layout 0 23 11 2 V
osd_layout 0 28 21 9 V
osd_layout 0 30 0 12 V
osd_layout 0 32 2 7 V
osd_layout 0 40 22 8 V
osd_layout 0 107 20 2 V
osd_layout 0 108 20 3 V
osd_layout 0 109 20 4 V
osd_layout 0 110 20 5 H
osd_layout 0 111 20 6 H

# master
set looptime = 500
set gyro_sync = OFF
set gyro_hardware_lpf = 256HZ
set gyro_lpf_hz = 90
set gyro_lpf_type = PT1
set gyro_stage2_lowpass_hz = 175
set dyn_notch_min_hz = 100
set acc_hardware = MPU6000
set acczero_x = 84
set acczero_z = -222
set accgain_x = 4093
set accgain_y = 4120
set accgain_z = 4045
set align_mag = CW0
set mag_hardware = HMC5883
set magzero_x = 75
set magzero_y = -70
set magzero_z = 36
set baro_hardware = BMP280
set pitot_hardware = NONE
set receiver_type = SERIAL
set min_check = 1020
set rssi_source = CHANNEL
set rc_filter_frequency = 40
set serialrx_provider = CRSF
set blackbox_rate_denom = 2
set motor_pwm_rate = 8000
set motor_pwm_protocol = DSHOT300
set throttle_idle =  6.000
set failsafe_procedure = RTH
set current_meter_scale = 270
set model_preview_type = 3
set applied_defaults = 2
set rpm_gyro_min_hz = 80
set gps_auto_config = OFF
set mc_airmode_type = THROTTLE_THRESHOLD
set nav_extra_arming_safety = OFF
set nav_rth_alt_mode = EXTRA
set nav_mc_hover_thr = 1230
set osd_video_system = PAL
set osd_coordinate_digits = 8
set i2c_speed = 200KHZ
set debug_mode = GYRO
set vtx_channel = 3
set vtx_power = 4
set vtx_low_power_disarm = UNTIL_FIRST_ARM
set vtx_freq = 5780

# profile
profile 1

set mc_p_pitch = 33
set mc_i_pitch = 52
set mc_d_pitch = 27
set mc_p_roll = 31
set mc_i_roll = 52
set mc_d_roll = 27
set mc_p_yaw = 60
set mc_i_yaw = 50
set max_angle_inclination_rll = 400
set max_angle_inclination_pit = 400
set dterm_lpf_hz = 75
set use_dterm_fir_filter = OFF
set nav_mc_vel_xy_d = 65
set d_boost_factor =  1.500
set antigravity_gain =  2.000
set antigravity_accelerator =  5.000
set rc_yaw_expo = 70
set roll_rate = 70
set pitch_rate = 70
set yaw_rate = 50

# battery_profile
battery_profile 1

set battery_capacity = 2200
set battery_capacity_warning = 440
set battery_capacity_critical = 220

# end the command batch
batch end

#