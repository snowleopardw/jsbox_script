
#### 2018.04.30

1. 修复TF无效（节点无udp-relay=true）的问题
2. 修复升级日志遮挡问题
3. 由于``$addin.save``没有回调，更新完后添加2s的延迟再重启（防止极端情况更新失败）

#### 2018.04.29

1. 不选Auto时，Auto则为DIRECT，生成后请手动选择Proxy
2. 保存的``托管``或``ss://``改为以名称显示（可能不能很好兼容上版本）
3. 增加倒序和全部添加到Auto功能
3. 调整界面大小
4. 修正无法识别托管文件名的问题