使用方法：
============================================================================================
创建 S3 Bucket
1.使用 maven 进行编译
2.在根目录下
/Users/hezhou/zh/IgnitionLearning/ignition-sdk-examples/AWSSDKS3
输入以下代码：
./run_example.sh CreateBucket test1

其中 CreateBucket 是主函数， test1 是 bucket name


============================================================================================
上传 object
1.使用 maven 进行编译
2.在根目录下
/Users/hezhou/zh/IgnitionLearning/ignition-sdk-examples/AWSSDKS3
输入以下代码：
./putobject.sh 'test1 /Users/hezhou/zh/语音识别.pdf'

这里注意，如果要输入两个参数，则要用单引号引起来，否则会出现 Unknown lifecycle phase


