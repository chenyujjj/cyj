# 股票策略交易系统-爬虫

#### 介绍
该项目是一个教学项目，不用于商业目的。
该项目的股票策略交易系统的爬虫部分，采用scrapy做为框架。爬取沪深300，股票交易信息，公司财务信息，汇率信息，公告信息。
收集的数据用于训练模型和评价策略。
1. 数据采集：爬取的网址包括沪深300指数，股票交易信息，公司财务信息，汇率信息，公告信息等。
2. 数据处理：对爬取的数据进行清洗和预处理，如去除无效数据，处理缺失值，数据类型转换等。
3. 数据存储：将处理后的数据存储到Mysql数据库中（一期）Hive(二期)，以便于后续的数据分析和模型训练。
4. 数据可视化：使用matplotlib，seaborn等库对数据进行可视化分析，以便更好地理解数据的特性和规律。
5. 模型训练：根据收集的数据训练股票策略交易模型，如线性回归，决策树，随机森林，神经网络等。
6. 模型评估：使用交叉验证等方法对模型进行评估，以确定模型的性能和稳定性。
7. 策略优化：根据模型的评估结果，优化股票交易策略，以提高投资回报。
8. 系统监控：实时监控股票交易市场的变化，以便及时调整策略。
#### 软件架构
爬虫部分采用scrapy做框架。
1、爬虫文件夹存放的是爬虫的工程文件
2、策略模型文件夹存放的是训练好的策略模型
3、练习文件夹，是日常练习的目标，会定期清除
4、预处理文件夹为数据预处理脚本目录


#### 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  马时易初



