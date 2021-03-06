DE-PART 是一个开源项目，结合IPFS 和代理重加密技术(Proxy Re-Encryption) 保障数据安全共享，为人们一个提供全生命周期健康管理系统。在数字世界2077中，将减少患者看病时需要的冗余手续，打通各个医院、以及医院和药房之间的信任壁垒，为病患提供最便捷的看病手续，为医院提供该病人最全的既往病史。DE-PART 项目特点如下：

1. 打通各个医院之间的数据孤岛，使病人到不同医院就诊无需多次重复检查、减少病人花销。
2. 就诊纪录彼此信任，通过数据上链存证解决不同医院诊断结果彼此信任、病人跨院购买处方药等问题。
3. 就诊数据溯源，可证明病历真实性，并将病历材料和保险打通。
4. 数据使用代理重加密技术(Proxy Re-Encryption) 去中心化存储，保证数据的安全性。
5. 密码学技术保证数据使用权归病人所有。

在我们的架构中：

- 使用PlatONE 联盟链存储病历的哈希信息，保障病历数据的可溯源及不可篡改。由万向区块链背书，建立“医院-药房-保险公司联盟”，管理医院及医生资质，同时管理保险公司和药房的准入。

- 代理重加密技术(Proxy Re-Encryption) 加密存储病历数据，保障链上个人医疗数据隐私，支持密文高效授权和分发，使链上数据拥有者能对数据进行高效共享。

- IPFS 等分布式存储技术保障了大数据的存储。
