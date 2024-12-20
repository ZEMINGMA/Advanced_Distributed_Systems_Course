# Advanced_Distributed_Systems_Course
    高级分布式系统实验

# 目录结构 

├── include
├── lib
│   ├── atom.cpp
│   ├── atom.h
│   ├── Executor.cpp
│   ├── Executor.h
│   ├── FixLengthInt.h
│   ├── Lock.cpp
│   ├── Lock.h
│   ├── Logger.cpp
│   ├── Logger.h
│   ├── mapi.cpp
│   ├── mapi.h
│   ├── Task.cpp
│   ├── Task.h
│   ├── Thread.cpp
│   └── Thread.h
├── README.md
└── src
    ├── main.cpp
    └── Paxos
        ├── Acceptor.cpp
        ├── Acceptor.h
        ├── PaxosData.h
        ├── Proposer.cpp
        └── Proposer.h

# 测试流程
mkdir build
cd build
cmake..
make
./paxos

# TODO
-[X] Acceptor
-[X] Proposer