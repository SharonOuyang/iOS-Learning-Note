## APP's Life Cycle

### Apps are always in one of five states,which are as belows （APP的5种状态）

### ![](/assets/apps_state.png)

      

* **Launch.**Your app transitions from the not running to the inactive or background state. Use this transition to prepare your app to run; see[Responding to the Launch of Your App](https://developer.apple.com/documentation/uikit/core_app/managing_your_app_s_life_cycle/responding_to_the_launch_of_your_app).

* **Activation.**Your app transitions from the inactive to the active state. Prepare your app to run in the foreground and be visible onscreen; see[Preparing Your App to Run in the Foreground](https://developer.apple.com/documentation/uikit/core_app/managing_your_app_s_life_cycle/preparing_your_app_to_run_in_the_foreground).

* **Deactivation.**Your app transitions from the active to the inactive state. Quiet your app, perhaps only temporarily; see[Preparing Your App to Run in the Background](https://developer.apple.com/documentation/uikit/core_app/managing_your_app_s_life_cycle/preparing_your_app_to_run_in_the_background).

* **Background execution.**Your app transitions from the inactive or not running state to the background state. Prepare to handle only essential tasks while running offscreen; see[Preparing Your App to Run in the Background](https://developer.apple.com/documentation/uikit/core_app/managing_your_app_s_life_cycle/preparing_your_app_to_run_in_the_background).

* **Termination.**Your app transitions from any running state to the not running state. \(Suspended apps are not notified when they are terminated.\) Cancel all tasks and prepare to exit; see[`applicationWillTerminate(_:)`](https://developer.apple.com/documentation/uikit/uiapplicationdelegate/1623111-applicationwillterminate).



### OS X Process Life Cycle 进程生命周期

### ![](/assets/OS X Life Cycle.png)



