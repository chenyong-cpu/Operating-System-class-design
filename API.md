<!--
 * @Author: ChenY
 * @Date: 2020-12-14 15:05:04
 * @LastEditTime: 2020-12-14 15:28:16
 * @FilePath: /leetcode/Project/FINISH/src/API.md
-->
// 一个返回所有文件名的API,把返回的所有文件名放在vector<string>里面
vector<string> getAllFileName();
// 创建文件，输入一个文件名称
bool createFileByFileName(string fileName);
// 删除文件的API，传入文件名
bool removeFileByFileName(string fileName);
// 一个根据文件名称获取文件数据内容的API，返回一个string文件内容
string getFileContentByFileName(string fileName);
// 更新文件内容的API，传入两个参数，一个为文件名，另外一个为文件内容
bool updateFileContentByFileName(string fileName, string fileContent);
// 根据文件名称获取文件属性
struct Directory getFileAttributeByFileName(string fileName);
// 更新文件名的API，传入两个参数，一个为原来的文件名，另外一个为新的文件名称
bool renameFileAttributeByFileName(string oldFileName, string newFileName);
