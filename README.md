# 爬取并分析苏南城市链家网租房房源全部数据，得出租房建议（苏南城市租房图鉴
项目主要爬取苏南四大城市链家网全部租房房源数据，并且得出租金分布、租房考虑因素等建议

主要的文件为：

  house_data_crawler.py：爬取北上广深租房房源数据的代码（带说明和注释, 需要安装mongodb）
  info.py：租房类型和各城市各区域的信息，供house_data_crawler.py调用
  北上广深租房图鉴.ipynb: Jupyter notebook代码，对北上广深租房数据进行分析
  data_sample.csv: 租房数据，这里只随机选择了12000条，每城市3000条
  
运行环境：

    python3.7

需要安装的包：

    requests
    pyecharts
    pandas
    numpy
    pymysql
