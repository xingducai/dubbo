### HttpProtocol doRefer方法中以下代码替换

spring4.x 将CommonsHttpInvokerRequestExecutor移除，替代HttpComponentsHttpInvokerRequestExecutor
            HttpComponentsHttpInvokerRequestExecutor
                    httpInvokerRequestExecutor = new HttpComponentsHttpInvokerRequestExecutor();
          