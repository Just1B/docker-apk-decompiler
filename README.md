# Step 1 Compile

docker build --tag=apkdecompiler .

# Step 2 Decompile

docker run --rm -v `pwd`:/app apkdecompiler d YOUR_APK.apk
