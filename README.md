# multi-android
Double Android system solutions

To enhance the security and customizability of Android system, a method based on the container technique on the Android system is proposed in this paper through analyzing the current virtualization technology. By sharing a Linux kernel, it can run multiple Android systems on one device simultaneously. First of all, we create multiple isolated operation space in the Linux kernel by using container and virtualization technology. In this paper we also implement the display device, Binder driver,GPU,WIFI and SIM virtualization for running an Android subsystem independently in each separated space, in order to achieve multiplexing equipment.
This project also studied and implemented quickly switch technology between Android subsystem, it allows for fast switching within 1 second, diverse switching mode, which can be switched by the program can also be switched by physical buttons.
Due to each container isolates from each other, this approach can effectively protect security of user’s data. Even if there is a running fault or malicious attacks in one of the Android subsystems, the other subsystems can still working correctly. So it can improve the security for whole system. And, the Applications and functions of each subsystem can be particularly customized to meet different requirements of users.
