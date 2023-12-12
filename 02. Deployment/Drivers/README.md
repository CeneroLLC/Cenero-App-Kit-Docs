# 🕸 Driver Deployment

Launch the appkit system utility and select the `Install Drivers` option.  Fill out the system IP address and authentication settings.  **NOTE: Virtual Control Servers and C3C-Nano require no deployment as they already have the driver loaded to the /cenero/drivers directory**

![Readme Image](./overview.gif)

## ✅ Verify Drivers

Driver are loaded to the *user/appkit* directory on the Crestron Processor.  To verify drivers have been loaded successfully use an `SFTP Client` or your choosing.  Note each apppkit subsystem will create a new child directory */user/appkit/audio*, */user/appkit/cameras* etc... **Note: on VC4 systems the user directory is relative to the room for example the user/appkit directory on a room called TEST would be located in the /opt/crestron/virtualcontro/RunningPrograms/TEST/user/appkit directory**

![Readme Image](./verifyfiles.gif)

## 🚪 Loading Drivers

From the appkit webpage these drivers should now be accessible from the driver loading dialogs for each subsystem.

![Readme Image](./loading.gif)

## 🧙‍♂️ Importing Drivers

The preloaded drivers on the C3C controllers can be imported from the disc to the rooms directory so they can be used by the system.  Select the 🧙‍♂️magic import divers button and select drivers to import. *Note this is ONLY displyed while running appkit applications on a VC4*.  If the restart room message is displayed a driver was replaces and the application needs to be restarted.

![Readme Image](./importing.gif)

## 📩 References

Driver Directories

![3-Series](https://img.shields.io/badge/3-SERIES-blue) *//USER//Appkit/*

![4-Series](https://img.shields.io/badge/4-SERIES-blue) */user/appkit/*

![VC4-Series](https://img.shields.io/badge/VC-4-blue) */opt/crestron/virtualcontro/RunningPrograms/ROOMID/user/appkit*

![C3C-Nano](https://img.shields.io/badge/C3C-Nano-blue) Preloaded drivers repo */cenero/drivers/*
