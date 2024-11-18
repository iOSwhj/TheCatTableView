一款结合 Alamofire 和 UITableViewDataSourcePrefetching 实现平滑无限滚动的 App。
该 App 使用 数据缓存 技术对网络数据加载进行了优化，并结合 UITableViewDataSourcePrefetching 机制，实现了流畅的滚动体验。为避免 UITableView 复用机制 导致的错误（如图片错乱或闪烁问题），设置了缓存验证、异步加载管理和复用标识的校验逻辑，从而确保用户体验的稳定性和一致性。
