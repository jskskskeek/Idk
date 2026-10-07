C:\Users\пользователь\Desktop\platform-tools>adb shell
Neo2:/ # ls -l /data/tombstones 2>/dev/null
1|Neo2:/ # ls -l /data/tombstones 2>/dev/null | tail
Neo2:/ # dmesg | tail -150
[  589.926930] (4)[320:charger_thread][fgauge_read_current] final current=3554 (ratio=1000)
[  589.926947] (4)[320:charger_thread][CH3_DBG] bat_cur = 3554
[  589.927576] (4)[320:charger_thread][fgauge_read_current] final current=3402 (ratio=1000)
[  589.927599] (4)[320:charger_thread][BattVoltToTemp] 738 24000 2802 -3
[  589.927619] (4)[320:charger_thread][force_get_tbat] 741,738,1,340,0,292 r:100 0 0
[  589.927637] (4)[320:charger_thread][force_get_tbat] t:29 precise:292
[  589.927661] (4)[320:charger_thread]pe40_ready:0 hv:1 thermal:-1,-1 tmp:29,39,16 pps:0 en:0 ibus:0 80
[  589.927687] (4)[320:charger_thread]mtk_tc30_start_algotithm: stop, tc30 is not connected
[  589.927706] (4)[320:charger_thread]mtk_pe20_start_algorithm: stop, PE+20 is not connected
[  589.927725] (4)[320:charger_thread]mtk_hvdcp20_start_algotithm: stop, hvdcp20 is not connected
[  589.927760] (4)[320:charger_thread]force:0 thermal:-1,-1 pe4:-1,-1,0 setting:500 500 type:1 usb_unlimited:0 usbif:0 usbsm:2 aicl:-1 atm:0
[  589.927784] (4)[320:charger_thread]rt9471 5-0053: __rt9471_set_aicr aicr = 500000(0x0A)
[  589.928434] (4)[320:charger_thread]rt9471 5-0053: __rt9471_set_ichg ichg = 500000(0x0A)
[  589.929060] (4)[320:charger_thread]rt9471 5-0053: rt9471_enable_charging en = 1
[  589.929086] (4)[320:charger_thread]rt9471 5-0053: __rt9471_enable_chg en = 1, chip_rev = 5
[  589.929566] (4)[320:charger_thread]rt9471 5-0053: __rt9471_set_cv cv = 4480000(0x3A)
[  589.930020] (4)[320:charger_thread]rt9471 5-0053: rt9471_enable_charging en = 1
[  589.930044] (4)[320:charger_thread]rt9471 5-0053: __rt9471_enable_chg en = 1, chip_rev = 5
[  589.930725] (4)[320:charger_thread]rt9471 5-0053: __rt9471_kick_wdt
[  589.933315] (4)[320:charger_thread]rt9471 5-0053: __rt9471_dump_registers MIVR = 4600mV, AICR = 500mA
[  589.933342] (4)[320:charger_thread]rt9471 5-0053: __rt9471_dump_registers CV = 4480mV, ICHG = 500mA, IEOC = 350mA
[  589.933364] (4)[320:charger_thread]rt9471 5-0053: __rt9471_dump_registers CHG_EN = 1, IC_STAT = fast-charge
[  589.933385] (4)[320:charger_thread]rt9471 5-0053: __rt9471_dump_registers STAT0 = 0xC1, STAT1 = 0x40
[  589.933405] (4)[320:charger_thread]rt9471 5-0053: __rt9471_dump_registers STAT2 = 0x00, STAT3 = 0x00
[  589.933425] (4)[320:charger_thread]rt9471 5-0053: __rt9471_dump_registers HIDDEN_2 = 0xE2
[  589.936353] (0)[3817:recovery]erofs: unmounted for /dev/block/dm-2
[  589.948069] (5)[3817:recovery]erofs: read_super, device -> /dev/block/dm-4
[  589.948082] (5)[3817:recovery]erofs: options ->
[  589.948316] (5)[3817:recovery]erofs: root inode @ nid 41
[  589.948562] (5)[3817:recovery]erofs: mounted on /dev/block/dm-4 with opts: .
[  589.976461] (0)[3817:recovery]erofs: unmounted for /dev/block/dm-4
[  589.995256] (1)[3817:recovery]EXT4-fs (mmcblk0p19): mounted filesystem with ordered data mode. Opts:
[  590.043218] (1)[3817:recovery]erofs: read_super, device -> /dev/block/dm-5
[  590.043242] (1)[3817:recovery]erofs: options ->
[  590.043811] (1)[3817:recovery]erofs: root inode @ nid 45
[  590.044095] (1)[3817:recovery]erofs: mounted on /dev/block/dm-5 with opts: .
[  590.160444] (1)[121:watchdogd][wdtk] kick watchdog
[  590.196766] (0)[3817:recovery]erofs: unmounted for /dev/block/dm-5
[  590.222187] (0)[3817:recovery][M4U] m4u_fb_notifier_callback 1, 9
[  590.222202] (0)[3817:recovery]mtk-tpd:[tpd_fb_notifier_callback:483] tpd_fb_notifier_callback
[  590.222213] (0)[3817:recovery]mtk-tpd:[tpd_fb_notifier_callback:488] fb_notify(event=1,blank=0)
[  590.222506] (0)[3817:recovery][PWM] disp_pwm_set_backlight_cmdq: (id = 0x1, level_1024 = 0), old = 500
[  590.222742] (0)[3817:recovery][PWM] disp_pwm_set_backlight_cmdq: (id = 0x1, level_1024 = 102), old = 0
[  590.233447] (0)[3817:recovery][M4U] m4u_fb_notifier_callback 1, 9
[  590.233462] (0)[3817:recovery]mtk-tpd:[tpd_fb_notifier_callback:483] tpd_fb_notifier_callback
[  590.233472] (0)[3817:recovery]mtk-tpd:[tpd_fb_notifier_callback:488] fb_notify(event=1,blank=0)
[  590.244388] (0)[3817:recovery][M4U] m4u_fb_notifier_callback 1, 9
[  590.244400] (0)[3817:recovery]mtk-tpd:[tpd_fb_notifier_callback:483] tpd_fb_notifier_callback
[  590.244410] (0)[3817:recovery]mtk-tpd:[tpd_fb_notifier_callback:488] fb_notify(event=1,blank=0)
[  590.244742] (0)[3817:recovery][PWM] disp_pwm_set_backlight_cmdq: (id = 0x1, level_1024 = 500), old = 102
[  590.245038] (0)[3817:recovery][PWM] disp_pwm_set_backlight_cmdq: (id = 0x1, level_1024 = 0), old = 500
[  590.245405] (0)[3817:recovery][PWM] disp_pwm_set_backlight_cmdq: (id = 0x1, level_1024 = 500), old = 0
[  590.435174] (6)[3817:recovery][M4U] m4u_fb_notifier_callback 1, 9
[  590.435181] (6)[3817:recovery]mtk-tpd:[tpd_fb_notifier_callback:483] tpd_fb_notifier_callback
[  590.435185] (6)[3817:recovery]mtk-tpd:[tpd_fb_notifier_callback:488] fb_notify(event=1,blank=0)
[  590.476675] (7)[3817:recovery]tran_gc:TRAN_GC v1.5 stopped.
[  590.477010] (2)[3826:TranGcStopExtra]------------[ cut here ]------------
[  590.477030] (2)[3826:TranGcStopExtra]name 'support_list'
[  590.477097] -(2)[3826:TranGcStopExtra]WARNING: CPU: 2 PID: 3826 at remove_proc_entry+0xe4/0x220
[  590.477109] -(2)[3826:TranGcStopExtra]Modules linked in:
[  590.477138] -(2)[3826:TranGcStopExtra]CPU: 2 PID: 3826 Comm: TranGcStopExtra Tainted: G S      W         4.19.191-ga82d73569ff0-dirty #1
[  590.477154] -(2)[3826:TranGcStopExtra]Hardware name: MT6769V/CZ (DT)
[  590.477173] -(2)[3826:TranGcStopExtra]pstate: 60c00005 (nZCv daif +PAN +UAO)
[  590.477192] -(2)[3826:TranGcStopExtra]pc : remove_proc_entry+0xe4/0x220
[  590.477210] -(2)[3826:TranGcStopExtra]lr : remove_proc_entry+0xe4/0x220
[  590.477225] -(2)[3826:TranGcStopExtra]sp : ffffff800e693dd0
[  590.477236] -(2)[3826:TranGcStopExtra]x29: ffffff800e693df0 x28: 0000000000000000
[  590.477257] -(2)[3826:TranGcStopExtra]x27: ffffffda59e172b8 x26: ffffffda5afa9880
[  590.477278] -(2)[3826:TranGcStopExtra]x25: 0000000000000000 x24: ffffffda5b6cbc00
[  590.477298] -(2)[3826:TranGcStopExtra]x23: 000000000000000c x22: 000000000000000c
[  590.477318] -(2)[3826:TranGcStopExtra]x21: ffffff961b4392e0 x20: ffffff961b4392e0
[  590.477338] -(2)[3826:TranGcStopExtra]x19: ffffffda5b433c00 x18: 0000000000000074
[  590.477358] -(2)[3826:TranGcStopExtra]x17: 0000000000000000 x16: ffffff961afd69a0
[  590.477375] -(2)[3826:TranGcStopExtra]x15: ffffff961b16ddef x14: 0000000000000050
[  590.477389] -(2)[3826:TranGcStopExtra]x13: 000000000002c9d6 x12: 0000000000000000
[  590.477399] -(2)[3826:TranGcStopExtra]x11: 0000000000000000 x10: 0000000000000007
[  590.477406] -(2)[3826:TranGcStopExtra]x9 : 29962ad2edac0500 x8 : 29962ad2edac0500
[  590.477414] -(2)[3826:TranGcStopExtra]x7 : 707075732720656d x6 : ffffff961b9e73b1
[  590.477421] -(2)[3826:TranGcStopExtra]x5 : 0000000000000ef2 x4 : 000000000000000c
[  590.477428] -(2)[3826:TranGcStopExtra]x3 : 000000000000003d x2 : 0000000000000007
[  590.477435] -(2)[3826:TranGcStopExtra]x1 : 0000000000000007 x0 : 000000000000002d
[  590.477443] -(2)[3826:TranGcStopExtra]Call trace:
[  590.477451] -(2)[3826:TranGcStopExtra] remove_proc_entry+0xe4/0x220
[  590.477460] -(2)[3826:TranGcStopExtra] tran_gc_stop_extra+0x220/0x254
[  590.477469] -(2)[3826:TranGcStopExtra] kthread+0x13c/0x14c
[  590.477477] -(2)[3826:TranGcStopExtra] ret_from_fork+0x10/0x18
[  590.477483] -(2)[3826:TranGcStopExtra]---[ end trace a1340cc1609672eb ]---
[  590.525685] (0)[3817:recovery]F2FS-fs (mmcblk0p49): Using encoding defined by superblock: utf8-12.1.0 with flags 0x0
[  590.529169] (0)[3817:recovery]F2FS-fs (mmcblk0p49): Reduce reserved blocks for root = 24927
[  590.567146] (6)[3817:recovery]F2FS-fs (mmcblk0p49): Found nat_bits in checkpoint
[  590.717124] (7)[3817:recovery]tran_gc:mount userdata f2fs tran_gc is going
[  590.717183] (7)[3817:recovery]sfi:ep02 enable, default
[  590.718018] (7)[3817:recovery][ark] enable ark for this partition {5207411c-c08f-4e00-aba3-77dfbf75a6ed}
[  590.718029] (7)[3817:recovery]F2FS-fs (mmcblk0p49): Mounted with checkpoint version = 737a287b
[  590.721132] (1)[375:logd.auditd]type=1400 audit(1791375023.120:1508): avc: denied { ioctl } for comm="recovery" path="/dev/block/dm-3" dev="tmpfs" ino=15524 ioctlcmd=0x5331 scontext=u:r:recovery:s0 tcontext=u:object_r:dm_device:s0 tclass=blk_file permissive=1
[  590.726525] (7)[3817:recovery]erofs: read_super, device -> /dev/block/dm-3
[  590.726533] (7)[3817:recovery]erofs: options ->
[  590.726667] (7)[3817:recovery]erofs: root inode @ nid 59
[  590.726809] (7)[3817:recovery]erofs: mounted on /dev/block/dm-3 with opts: .
[  590.727434] (2)[375:logd.auditd]type=1400 audit(1791375023.124:1509): avc: denied { ioctl } for comm="recovery" path="/dev/block/dm-5" dev="tmpfs" ino=15530 ioctlcmd=0x5331 scontext=u:r:recovery:s0 tcontext=u:object_r:dm_device:s0 tclass=blk_file permissive=1
[  590.732748] (7)[3817:recovery]erofs: read_super, device -> /dev/block/dm-5
[  590.732757] (7)[3817:recovery]erofs: options ->
[  590.732930] (7)[3817:recovery]erofs: root inode @ nid 45
[  590.733082] (7)[3817:recovery]erofs: mounted on /dev/block/dm-5 with opts: .
[  590.768400] (6)[3817:recovery]erofs: unmounted for /dev/block/dm-5
[  590.784402] (7)[3817:recovery]erofs: unmounted for /dev/block/dm-3
[  590.785314] (0)[375:logd.auditd]type=1400 audit(1791375023.184:1510): avc: denied { ioctl } for comm="recovery" path="/dev/block/dm-3" dev="tmpfs" ino=15524 ioctlcmd=0x5331 scontext=u:r:recovery:s0 tcontext=u:object_r:dm_device:s0 tclass=blk_file permissive=1
[  590.792074] (0)[3817:recovery]erofs: read_super, device -> /dev/block/dm-3
[  590.792087] (0)[3817:recovery]erofs: options ->
[  590.792333] (0)[3817:recovery]erofs: root inode @ nid 59
[  590.792571] (0)[3817:recovery]erofs: mounted on /dev/block/dm-3 with opts: .
[  590.832456] (0)[3817:recovery]erofs: unmounted for /dev/block/dm-3
[  590.833578] (1)[375:logd.auditd]type=1400 audit(1791375023.232:1511): avc: denied { ioctl } for comm="recovery" path="/dev/block/dm-3" dev="tmpfs" ino=15524 ioctlcmd=0x5331 scontext=u:r:recovery:s0 tcontext=u:object_r:dm_device:s0 tclass=blk_file permissive=1
[  590.841352] (2)[3817:recovery]erofs: read_super, device -> /dev/block/dm-3
[  590.841364] (2)[3817:recovery]erofs: options ->
[  590.841596] (2)[3817:recovery]erofs: root inode @ nid 59
[  590.841930] (3)[3817:recovery]erofs: mounted on /dev/block/dm-3 with opts: .
[  590.860542] (1)[3817:recovery]erofs: unmounted for /dev/block/dm-3
[  590.862078] (0)[375:logd.auditd]type=1400 audit(1791375023.260:1512): avc: denied { ioctl } for comm="recovery" path="/dev/block/dm-5" dev="tmpfs" ino=15530 ioctlcmd=0x5331 scontext=u:r:recovery:s0 tcontext=u:object_r:dm_device:s0 tclass=blk_file permissive=1
[  590.871797] (5)[3817:recovery]erofs: read_super, device -> /dev/block/dm-5
[  590.871827] (5)[3817:recovery]erofs: options ->
[  590.872524] (5)[3817:recovery]erofs: root inode @ nid 45
[  590.872820] (5)[3817:recovery]erofs: mounted on /dev/block/dm-5 with opts: .
[  590.896502] (0)[3817:recovery]erofs: unmounted for /dev/block/dm-5
[  590.898067] (1)[375:logd.auditd]type=1400 audit(1791375023.296:1513): avc: denied { ioctl } for comm="recovery" path="/dev/block/dm-2" dev="tmpfs" ino=13450 ioctlcmd=0x5331 scontext=u:r:recovery:s0 tcontext=u:object_r:dm_device:s0 tclass=blk_file permissive=1
[  590.908106] (5)[3817:recovery]erofs: read_super, device -> /dev/block/dm-2
[  590.908130] (5)[3817:recovery]erofs: options ->
[  590.908843] (5)[3817:recovery]erofs: root inode @ nid 38
[  590.909169] (5)[3817:recovery]erofs: mounted on /dev/block/dm-2 with opts: .
[  590.948541] (0)[3817:recovery]erofs: unmounted for /dev/block/dm-2
[  590.949958] (1)[375:logd.auditd]type=1400 audit(1791375023.348:1514): avc: denied { ioctl } for comm="recovery" path="/dev/block/dm-4" dev="tmpfs" ino=15527 ioctlcmd=0x5331 scontext=u:r:recovery:s0 tcontext=u:object_r:dm_device:s0 tclass=blk_file permissive=1
[  590.958330] (5)[3817:recovery]erofs: read_super, device -> /dev/block/dm-4
[  590.958341] (5)[3817:recovery]erofs: options ->
[  590.958570] (5)[3817:recovery]erofs: root inode @ nid 41
[  590.958803] (5)[3817:recovery]erofs: mounted on /dev/block/dm-4 with opts: .
[  590.976504] (0)[3817:recovery]erofs: unmounted for /dev/block/dm-4
[  591.124576] -(0)[0:swapper/0][name:spm&]Power/swap CNT(IdleDram): [0] = (0), [1] = (0), [2] = (0), [3] = (0), [4] = (0), [5] = (0), [6] = (0), [7] = (0),
[  591.124584] -(0)[0:swapper/0][name:spm&]Power/swap IdleDram_block_cnt: [BY_FRM] = 1594,
[  591.124599] -(0)[0:swapper/0][name:spm&]Power/swap IdleDram_block_mask: 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, 0x00000000, idle_pll_block_mask: 0x00000000\x0a
[  591.124607] -(0)[0:swapper/0][name:spm&][resource_req_block] user: 0x4, 0x0
[  591.167074] (2)[3817:recovery]EXT4-fs (mmcblk0p17): mounted filesystem with ordered data mode. Opts:
[  591.202418] (4)[3817:recovery]EXT4-fs (mmcblk0p18): mounted filesystem with ordered data mode. Opts:
[  591.233849] (4)[3817:recovery]EXT4-fs (mmcblk0p19): mounted filesystem with ordered data mode. Opts:
[  591.267691] (4)[3817:recovery]EXT4-fs (mmcblk0p20): mounted filesystem with ordered data mode. Opts:
[  591.310970] (5)[3817:recovery]EXT4-fs (mmcblk0p21): mounted filesystem with ordered data mode. Opts:
[  591.340993] (4)[3817:recovery]EXT4-fs (mmcblk0p48): mounted filesystem with ordered data mode. Opts:
[  591.370682] (4)[3817:recovery]EXT4-fs (mmcblk0p15): mounted filesystem with ordered data mode. Opts: discard
[  591.596173] (4)[0:swapper/4][name:spm&]Power/swap IdleBus26m: No enter --- IdleSyspll: No enter --- IdleDram: No enter ---
[  591.596194] (3)[0:swapper/3]mcdi cpu: 635, 512, 410, 299, 229, 218, 355, 118, cluster : 144, pause = 0, multi core = 83, latency = 0, residency = 393, last core = 260, avail cpu = 00ff, cluster = 0001, enabled = 1, max_s_state = 5, system_idle_hint = 00000000
[  591.735848] (6)[3817:recovery][SDD]: do_coredump.
Neo2:/ # logcat -d -b crash | tail -250
10-07 12:05:43.774  2177  2177 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:05:43.774  2177  2177 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:05:48.794  2206  2206 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2206 (recovery), pid 2206 (recovery)
10-07 12:05:48.796  2232  2232 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:05:48.798  2206  2206 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:05:48.799  2206  2206 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:05:53.770  2234  2234 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2234 (recovery), pid 2234 (recovery)
10-07 12:05:53.772  2267  2267 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:05:53.774  2234  2234 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:05:53.774  2234  2234 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:05:58.808  2271  2271 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2271 (recovery), pid 2271 (recovery)
10-07 12:05:58.811  2297  2297 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:05:58.813  2271  2271 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:05:58.813  2271  2271 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:03.800  2301  2301 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2301 (recovery), pid 2301 (recovery)
10-07 12:06:03.803  2328  2328 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:03.805  2301  2301 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:03.805  2301  2301 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:08.809  2330  2330 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2330 (recovery), pid 2330 (recovery)
10-07 12:06:08.812  2357  2357 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:08.814  2330  2330 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:08.814  2330  2330 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:13.717  2359  2359 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2359 (recovery), pid 2359 (recovery)
10-07 12:06:13.719  2386  2386 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:13.721  2359  2359 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:13.722  2359  2359 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:18.896  2389  2389 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2389 (recovery), pid 2389 (recovery)
10-07 12:06:18.898  2415  2415 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:18.900  2389  2389 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:18.901  2389  2389 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:23.716  2418  2418 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2418 (recovery), pid 2418 (recovery)
10-07 12:06:23.719  2444  2444 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:23.720  2418  2418 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:23.720  2418  2418 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:28.843  2447  2447 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2447 (recovery), pid 2447 (recovery)
10-07 12:06:28.845  2473  2473 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:28.848  2447  2447 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:28.848  2447  2447 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:33.836  2476  2476 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2476 (recovery), pid 2476 (recovery)
10-07 12:06:33.840  2502  2502 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:33.841  2476  2476 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:33.841  2476  2476 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:38.776  2505  2505 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2505 (recovery), pid 2505 (recovery)
10-07 12:06:38.779  2531  2531 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:38.780  2505  2505 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:38.780  2505  2505 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:43.755  2533  2533 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2533 (recovery), pid 2533 (recovery)
10-07 12:06:43.757  2560  2560 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:43.759  2533  2533 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:43.760  2533  2533 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:48.781  2563  2563 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2563 (recovery), pid 2563 (recovery)
10-07 12:06:48.784  2589  2589 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:48.785  2563  2563 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:48.785  2563  2563 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:53.861  2592  2592 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2592 (recovery), pid 2592 (recovery)
10-07 12:06:53.864  2619  2619 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:53.866  2592  2592 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:53.866  2592  2592 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:06:58.892  2623  2623 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2623 (recovery), pid 2623 (recovery)
10-07 12:06:58.896  2649  2649 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:06:58.897  2623  2623 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:06:58.897  2623  2623 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:03.860  2651  2651 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2651 (recovery), pid 2651 (recovery)
10-07 12:07:03.863  2678  2678 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:03.865  2651  2651 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:03.865  2651  2651 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:08.888  2681  2681 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2681 (recovery), pid 2681 (recovery)
10-07 12:07:08.891  2707  2707 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:08.893  2681  2681 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:08.893  2681  2681 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:13.852  2709  2709 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2709 (recovery), pid 2709 (recovery)
10-07 12:07:13.855  2736  2736 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:13.857  2709  2709 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:13.857  2709  2709 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:18.845  2739  2739 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2739 (recovery), pid 2739 (recovery)
10-07 12:07:18.848  2765  2765 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:18.850  2739  2739 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:18.850  2739  2739 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:23.864  2767  2767 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2767 (recovery), pid 2767 (recovery)
10-07 12:07:23.867  2794  2794 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:23.868  2767  2767 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:23.868  2767  2767 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:28.804  2797  2797 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2797 (recovery), pid 2797 (recovery)
10-07 12:07:28.806  2823  2823 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:28.809  2797  2797 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:28.809  2797  2797 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:33.921  2826  2826 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2826 (recovery), pid 2826 (recovery)
10-07 12:07:33.924  2852  2852 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:33.926  2826  2826 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:33.926  2826  2826 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:38.916  2854  2854 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2854 (recovery), pid 2854 (recovery)
10-07 12:07:38.919  2881  2881 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:38.921  2854  2854 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:38.921  2854  2854 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:43.969  2884  2884 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2884 (recovery), pid 2884 (recovery)
10-07 12:07:43.972  2911  2911 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:43.974  2884  2884 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:43.974  2884  2884 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:48.923  2914  2914 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2914 (recovery), pid 2914 (recovery)
10-07 12:07:48.926  2940  2940 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:48.928  2914  2914 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:48.929  2914  2914 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:53.923  2943  2943 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2943 (recovery), pid 2943 (recovery)
10-07 12:07:53.926  2969  2969 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:53.928  2943  2943 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:53.928  2943  2943 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:07:58.924  2972  2972 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 2972 (recovery), pid 2972 (recovery)
10-07 12:07:58.927  2998  2998 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:07:58.929  2972  2972 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:07:58.929  2972  2972 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:03.858  3000  3000 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3000 (recovery), pid 3000 (recovery)
10-07 12:08:03.861  3027  3027 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:03.863  3000  3000 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:03.863  3000  3000 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:09.005  3030  3030 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3030 (recovery), pid 3030 (recovery)
10-07 12:08:09.007  3056  3056 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:09.009  3030  3030 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:09.010  3030  3030 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:13.921  3058  3058 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3058 (recovery), pid 3058 (recovery)
10-07 12:08:13.924  3085  3085 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:13.926  3058  3058 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:13.926  3058  3058 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:18.914  3087  3087 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3087 (recovery), pid 3087 (recovery)
10-07 12:08:18.916  3114  3114 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:18.918  3087  3087 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:18.918  3087  3087 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:23.857  3116  3116 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3116 (recovery), pid 3116 (recovery)
10-07 12:08:23.860  3143  3143 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:23.861  3116  3116 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:23.861  3116  3116 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:29.052  3146  3146 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3146 (recovery), pid 3146 (recovery)
10-07 12:08:29.055  3172  3172 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:29.057  3146  3146 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:29.057  3146  3146 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:33.977  3175  3175 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3175 (recovery), pid 3175 (recovery)
10-07 12:08:33.980  3201  3201 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:33.982  3175  3175 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:33.982  3175  3175 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:39.008  3204  3204 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3204 (recovery), pid 3204 (recovery)
10-07 12:08:39.011  3230  3230 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:39.012  3204  3204 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:39.012  3204  3204 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:44.052  3233  3233 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3233 (recovery), pid 3233 (recovery)
10-07 12:08:44.056  3259  3259 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:44.057  3233  3233 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:44.057  3233  3233 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:48.953  3262  3262 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3262 (recovery), pid 3262 (recovery)
10-07 12:08:48.956  3288  3288 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:48.958  3262  3262 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:48.958  3262  3262 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:54.041  3291  3291 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3291 (recovery), pid 3291 (recovery)
10-07 12:08:54.043  3317  3317 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:54.045  3291  3291 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:54.046  3291  3291 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:08:59.038  3319  3319 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3319 (recovery), pid 3319 (recovery)
10-07 12:08:59.040  3346  3346 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:08:59.042  3319  3319 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:08:59.042  3319  3319 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:04.025  3348  3348 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3348 (recovery), pid 3348 (recovery)
10-07 12:09:04.028  3375  3375 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:04.030  3348  3348 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:04.030  3348  3348 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:09.024  3380  3380 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3380 (recovery), pid 3380 (recovery)
10-07 12:09:09.027  3406  3406 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:09.029  3380  3380 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:09.029  3380  3380 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:14.039  3409  3409 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3409 (recovery), pid 3409 (recovery)
10-07 12:09:14.042  3435  3435 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:14.044  3409  3409 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:14.044  3409  3409 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:19.010  3438  3438 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3438 (recovery), pid 3438 (recovery)
10-07 12:09:19.012  3464  3464 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:19.014  3438  3438 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:19.014  3438  3438 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:23.928  3466  3466 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3466 (recovery), pid 3466 (recovery)
10-07 12:09:23.931  3493  3493 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:23.933  3466  3466 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:23.933  3466  3466 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:29.085  3496  3496 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3496 (recovery), pid 3496 (recovery)
10-07 12:09:29.088  3522  3522 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:29.090  3496  3496 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:29.090  3496  3496 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:34.086  3525  3525 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3525 (recovery), pid 3525 (recovery)
10-07 12:09:34.088  3551  3551 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:34.090  3525  3525 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:34.090  3525  3525 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:39.184  3555  3555 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3555 (recovery), pid 3555 (recovery)
10-07 12:09:39.187  3581  3581 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:39.189  3555  3555 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:39.189  3555  3555 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:44.052  3583  3583 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3583 (recovery), pid 3583 (recovery)
10-07 12:09:44.055  3610  3610 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:44.057  3583  3583 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:44.057  3583  3583 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:49.120  3613  3613 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3613 (recovery), pid 3613 (recovery)
10-07 12:09:49.123  3639  3639 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:49.125  3613  3613 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:49.125  3613  3613 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:54.188  3642  3642 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3642 (recovery), pid 3642 (recovery)
10-07 12:09:54.191  3668  3668 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:54.192  3642  3642 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:54.192  3642  3642 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:09:59.077  3671  3671 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3671 (recovery), pid 3671 (recovery)
10-07 12:09:59.080  3697  3697 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:09:59.082  3671  3671 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:09:59.082  3671  3671 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:04.086  3702  3702 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3702 (recovery), pid 3702 (recovery)
10-07 12:10:04.089  3728  3728 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:04.091  3702  3702 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:04.091  3702  3702 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:09.141  3731  3731 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3731 (recovery), pid 3731 (recovery)
10-07 12:10:09.144  3757  3757 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:09.146  3731  3731 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:09.146  3731  3731 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:14.213  3760  3760 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3760 (recovery), pid 3760 (recovery)
10-07 12:10:14.216  3786  3786 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:14.218  3760  3760 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:14.218  3760  3760 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:19.191  3789  3789 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3789 (recovery), pid 3789 (recovery)
10-07 12:10:19.194  3815  3815 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:19.196  3789  3789 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:19.196  3789  3789 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:24.130  3817  3817 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3817 (recovery), pid 3817 (recovery)
10-07 12:10:24.135  3846  3846 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:24.136  3817  3817 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:24.137  3817  3817 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:29.149  3849  3849 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3849 (recovery), pid 3849 (recovery)
10-07 12:10:29.152  3876  3876 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:29.154  3849  3849 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:29.154  3849  3849 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:34.109  3878  3878 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3878 (recovery), pid 3878 (recovery)
10-07 12:10:34.111  3905  3905 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:34.113  3878  3878 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:34.113  3878  3878 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:39.170  3908  3908 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3908 (recovery), pid 3908 (recovery)
10-07 12:10:39.172  3934  3934 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:39.174  3908  3908 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:39.174  3908  3908 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:44.099  3936  3936 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3936 (recovery), pid 3936 (recovery)
10-07 12:10:44.101  3963  3963 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:44.103  3936  3936 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:44.103  3936  3936 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:49.095  3965  3965 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3965 (recovery), pid 3965 (recovery)
10-07 12:10:49.098  3992  3992 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:49.100  3965  3965 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:49.100  3965  3965 F libc    : failed to wait for crash_dump helper: No child processes
10-07 12:10:54.183  3995  3995 F libc    : Fatal signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x20 in tid 3995 (recovery), pid 3995 (recovery)
10-07 12:10:54.186  4021  4021 F libc    : failed to exec crash_dump helper: No such file or directory
10-07 12:10:54.188  3995  3995 F libc    : crash_dump helper failed to exec, or was killed
10-07 12:10:54.188  3995  3995 F libc    : failed to wait for crash_dump helper: No child processes
Neo2:/ # cat /proc/$(pidof recovery)/maps 2>/dev/null | head -100
Neo2:/ #
