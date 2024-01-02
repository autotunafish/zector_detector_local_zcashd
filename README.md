# zector_detector_local_zcashd
A local explorer that uses a local zcashd node for querying information.

* Create a local Zcash node.
* Use the Node IP Address Endpoint and RPC User and Password.
* 
* For Linux, Requires Rust and inotifytools
*
* git clone https://github.com/autotunafish/zector_detector_local_zcashd.git
* cd zector_detector_local_zcashd
* cargo run
* 
* Apply executable permissions to
* * /action_notify
  * /action_notify_b
  * /chain_notify
  * /chaininfo1.txt
  * /action1.txt
  * /action4.txt
* 
* You will be prompted to input your Node IP Address and RPC credentials.
* Enter the RPC User and Password in the format: User:Password
* 
* Hit Enter To Refresh Info, Input TX Hash Or Block Hash/Height
* Input 'R' For Raw Json
