# WinningModule

查房
****

|Author|ZY|
|---|---
|E-mail|510665117@qq.com


##  use:     pod 'WinningModule'  

shell:  
pod spec create WinningModule  
pod repo add WinningModule https://e.coding.net/winningmodulelib/WinningModuleLib.git  
git tag -m"pod spec" "0.0.1"  
git push origin --tags  
pod trunk me(login in)  
pod lib lint --allow-warnings --use-libraries --skip-import-validation  
pod spec lint WinningModule.podspec  --verbose --use-libraries --allow-warnings --skip-import-validation    
pod repo push WinningModule.podspec --allow-warnings --use-libraries --skip-import-validation --verbose
