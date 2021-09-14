# LoginWithGmail
Login dengan Akun Gmail

1. buka site
developer.google.com/identity/sign-in/android/start-integrating

2. copy kan ke gradle
implementation 'com.google.android.gms:play-services-auth:19.2.0'


3. buat project di(in) console developer
https://console.developers.google.com
create project in developer console

4. selanjutnya klik Configure a project pada situs developer.google.com tadi
now configure the created project

5. isikan nama project, dan next
6. pilih Android pada Configure your OAuth client, dan package name isikan nama project androidmu.




tambahan:
untuk create SHAkey dari android studio,
1.klik settings,klik experimental, dan uncheck do not build gradle task list during gradle sync.
2.cari signingReport,lalu double klik file tersebut.
dan isikan configure a project dengan nama project yang sudah dibuat tadi.(point 3), klik next



selanjutnya coding, panduan coding ada pada developer.google.com/identity/sign-in/android/start-integrating
