# KettleTree
Kettle数据转换技术研究


<pre>
Pentaho：
        
        是一个以工作流为核心的，强调面向解决方案的开源商业智能套件，以构成全面的数据集成和
      业务分析平台。

      Kettle是Pentaho整个产品体系中的数据集成模块，使用突破性的元数据驱动方法提供强大
      的“提取，转换和加载（ETL）”功能。主要使用在数据仓库环境下，同时还可以：在应用程序或数
      据库之间进行数据迁移、将数据从数据库中导出到文本文件中、将大量数据加载到数据库中、数据
      清理、应用程序集成等。作为最受欢迎的开源ETL工具，其支持大量的输入和输出格式，包括文本
      文件、数据表，以及各类商业或开源的数据库引擎。除此之外，Kettle还易于使用，用户可通过图
      形化界面定义任务或转换，无需编写代码。当然，Kettle支持用户使用脚本语言定义更加丰富的个性化功能。

      Spoon：
            Kettle的可视化集成开发环境。提供一个图形化用户界面，用户可以以拖拽的方式创建、
      定义作业或转换。另外，Spoon还可以用于执行、调试用户定义的作业或转换，及时看到实际效
      果，以提升用户开发和测试效率。对于远程执行或集群模式，Spoon可以监控各个子节点的作业或
      转换执行情况。下图为Spoon的操作界面，其中有一个定义好的作业流。
</pre>

<pre>
Kettle家族

      1) Spoon
         允许用户通过图形化界面来设计ETL转换过程。

      2) Pan
         允许用户批量运行由Spoon设计的ETL转换，Pan是一个后台执行的程序，没有图形界面。

      3) CHEF
         允许用户创建任务JOB，任务通过执行每个转换，任务，脚本等，更有利于自动化更新数据局仓库的复杂工作，
         任务将会被检查，看看是否正确运行了。

      5) Kitchen
         用于执行作业，允许你批量使用由Chef设计的任务，Kitchen也是一个后台运行的程序
</pre>