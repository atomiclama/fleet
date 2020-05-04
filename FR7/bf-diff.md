```
diff

# version
# Betaflight / STM32F405 (S405) 4.2.0 Mar 23 2020 / 01:07:08 (0bbe52ba2) MSP API: 1.43
# manufacturer_id: AIRB   board_name: OMNIBUSF4V6   custom defaults: YES

# start the command batch
batch start

board_name OMNIBUSF4V6
manufacturer_id AIRB

# resources
resource MOTOR 1 A03
resource MOTOR 2 B00
resource MOTOR 3 B05
resource MOTOR 4 B01

# mixer
mixer CUSTOM
mmix 0  1.000 -0.809  0.659 -1.000
mmix 1  1.000 -1.000 -0.659  1.000
mmix 2  1.000  0.809  0.659  1.000
mmix 3  1.000  1.000 -0.659 -1.000

# feature
feature GPS

# beeper
beeper -ON_USB

# beacon
beacon RX_LOST

# serial
serial 0 64 115200 57600 0 115200
serial 1 8192 115200 57600 0 115200
serial 5 2 115200 57600 0 115200

# aux
aux 0 0 1 1600 2100 0 0
aux 1 2 5 1600 2100 0 0
aux 2 46 0 1600 2100 0 0

# vtxtable
vtxtable bands 5
vtxtable channels 8
vtxtable band 1 BOSCAM_A A CUSTOM  5865 5845 5825 5805 5785 5765 5745 5725
vtxtable band 2 BOSCAM_B B CUSTOM  5733 5752 5771 5790 5809 5828 5847 5866
vtxtable band 3 BOSCAM_E E CUSTOM  5705 5685 5665 5645 5885 5905 5925 5945
vtxtable band 4 FATSHARK F CUSTOM  5740 5760 5780 5800 5820 5840 5860 5880
vtxtable band 5 RACEBAND R CUSTOM  5658 5695 5732 5769 5806 5843 5880 5917
vtxtable powerlevels 3
vtxtable powervalues 25 200 400
vtxtable powerlabels 25 200 500

# master
set dyn_notch_min_hz = 80
set dyn_notch_max_hz = 250
set acc_calibration = -41,1,350,1
set mag_hardware = NONE
set min_check = 1020
set rssi_channel = 14
set serialrx_provider = IBUS
set blackbox_p_ratio = 64
set dshot_bidir = ON
set motor_pwm_protocol = DSHOT300
set failsafe_procedure = GPS-RESCUE
set align_board_roll = 180
set ibata_scale = 1400
set yaw_motors_reversed = ON
set small_angle = 180
set gps_provider = UBLOX
set gps_sbas_mode = WAAS
set gps_auto_baud = ON
set gps_rescue_min_sats = 5
set gps_rescue_allow_arming_without_fix = ON
set deadband = 2
set yaw_deadband = 5
set pid_process_denom = 1
set osd_rssi_alarm = 50
set osd_tim1 = 2561
set osd_rssi_pos = 2089
set osd_tim_1_pos = 2262
set osd_current_pos = 2273
set osd_mah_drawn_pos = 2326
set osd_gps_speed_pos = 2242
set osd_gps_lon_pos = 2498
set osd_gps_lat_pos = 2511
set osd_gps_sats_pos = 2096
set osd_home_dir_pos = 2094
set osd_home_dist_pos = 2156
set osd_flight_dist_pos = 2295
set osd_warnings_pos = 14760
set osd_avg_cell_voltage_pos = 2306
set osd_stat_rtc_date_time = ON
set osd_stat_max_dist = ON
set osd_stat_flight_dist = ON
set osd_stat_total_time = ON
set debug_mode = GYRO_SCALED
set vtx_power = 2
set vtx_freq = 5780
set vcd_video_system = PAL
set gyro_1_align_yaw = 1800

profile 0

rateprofile 0

# end the command batch
batch end

# 