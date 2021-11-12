1. `cd weinre.build`
1. `cp sample.personal.properties personal.properties`
  - If you receive a `Execute failed: java.io.IOException: Cannot run program "growlnotify"` error, you can quickly fix it by commenting out `#USE_GROWL: yup` in `personal.properties`.
1. `ant` in `/weinre.build`
1. `cd ../weinre.server`
1. `./weinre --httpPort=8001 --boundHost=$MY_IP`
