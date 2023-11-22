FROM tmvdl/android:app

WORKDIR /app

RUN cordova create dadosabertos com.brtmvdl.dadosabertos dadosabertos

WORKDIR /app/dadosabertos

COPY app www

COPY cp.sh .

RUN cordova platform add android

RUN cordova build android
