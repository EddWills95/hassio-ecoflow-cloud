## STREAM_AC

*Sensors*
- Cumulative Capacity Charge (mAh) (`accuChgCap`)   _(disabled)_
- Cumulative Energy Charge (Wh) (`accuChgEnergy`)   _(disabled)_
- Cumulative Capacity Discharge (mAh) (`accuDsgCap`)   _(disabled)_
- Cumulative Energy Discharge (Wh) (`accuDsgEnergy`)   _(disabled)_
- Charge Remaining Time (`bmsChgRemTime`)   _(disabled)_
- Discharge Remaining Time (`bmsDsgRemTime`)   _(disabled)_
- Stored Energy (`storedEnergy_cmsBattFullEnergy`)
- Cycles (`cycles`)   _(disabled)_
- Design Capacity (`designCap`)   _(disabled)_
- Power Battery SOC (`f32ShowSoc`)   _(disabled)_
- Full Capacity (`fullCap`)   _(disabled)_
- Power AC (`gridConnectionPower`)
- Power Volts (`gridConnectionVol`)   _(disabled)_
- In Power (`inputWatts`)   _(disabled)_
- Max Cell Temperature (`maxCellTemp`)   _(disabled)_
- Max Cell Volts (`maxCellVol`)   _(disabled)_
- Min Cell Temperature (`minCellTemp`)   _(disabled)_
- Min Cell Volts (`minCellVol`)   _(disabled)_
- Out Power (`outputWatts`)   _(disabled)_
- Power Battery (`powGetBpCms`)
- Power PV 1 (`powGetPv`)   _(auto)_
- Power PV 2 (`powGetPv2`)   _(auto)_
- Power PV 3 (`powGetPv3`)   _(auto)_
- Power PV 4 (`powGetPv4`)   _(auto)_
- Power PV Sum (`powGetPvSum`)
- Power SCHUKO1 (`powGetSchuko1`)   _(auto)_
- Power SCHUKO2 (`powGetSchuko2`)   _(auto)_
- Power Grid (`powGetSysGrid`)
- Power Sys Load (`powGetSysLoad`)
- Power Sys Load From Battery (`powGetSysLoadFromBp`)
- Power Sys Load From Grid (`powGetSysLoadFromGrid`)
- Power Sys Load From PV (`powGetSysLoadFromPv`)
- Real State of Health (`realSoh`)   _(disabled)_
- Remain Capacity (`remainCap`)   _(disabled)_
- Remaining Time (`remainTime`)   _(disabled)_
- Power Battery (`soc`)   _(disabled)_
- State of Health (`soh`)   _(disabled)_
- Power AC SYS (`sysGridConnectionPower`)   _(disabled)_
- Battery Temperature (`temp`)   _(disabled)_
- Battery Volts (`vol`)   _(disabled)_

*Sliders (numbers)*
- Max Charge Level (`cmsMaxChgSoc` -> `{"StreamACSendHeaderMsg": {"msg": {"pdata": {"cms_max_chg_soc": 6666}, "src": 32, "dest": 2, "d_src": 1, "d_dest": 1, "cmd_func": 254, "cmd_id": 17, "data_len": 4, "need_ack": 1, "seq": 999921584, "product_id": 56, "version": 19, "payload_ver": 1, "device_sn": "SN"}}}` [5 - 100])
- Min Discharge Level (`cmsMinDsgSoc` -> `{"StreamACSendHeaderMsg": {"msg": {"pdata": {"cms_min_dsg_soc": 6666}, "src": 32, "dest": 2, "d_src": 1, "d_dest": 1, "cmd_func": 254, "cmd_id": 17, "data_len": 4, "need_ack": 1, "seq": 999997600, "product_id": 56, "version": 19, "payload_ver": 1, "device_sn": "SN"}}}` [0 - 30])
- Feed-in Power Limit (`feedGridModePowLimit` -> `{"StreamACSendHeaderMsg": {"msg": {"pdata": {"feed_grid_mode_pow_limit": 6666}, "src": 32, "dest": 2, "d_src": 1, "d_dest": 1, "cmd_func": 254, "cmd_id": 17, "data_len": 4, "need_ack": 1, "seq": 999948751, "product_id": 56, "version": 19, "payload_ver": 1, "device_sn": "SN"}}}` [0 - 800])
- Grid Charge Power Limit (`sysGridInPwrLimit` -> `{"StreamACSendHeaderMsg": {"msg": {"pdata": {"sys_grid_in_pwr_limit": 6666}, "src": 32, "dest": 2, "d_src": 1, "d_dest": 1, "cmd_func": 254, "cmd_id": 17, "data_len": 4, "need_ack": 1, "seq": 999961168, "product_id": 56, "version": 19, "payload_ver": 1, "device_sn": "SN"}}}` [0 - 4462])


