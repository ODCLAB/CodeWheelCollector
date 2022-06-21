```cpp
long RegQueryInfoKey (
HKEY hKey, 
LPWSTR lpClass, 
LPDWORD lpcbClass, 
LPDWORD lpReserved, 
LPDWORD lpcSubKeys, 
LPDWORD lpcbMaxSubKeyLen, 
LPDWORD lpcbMaxClassLen, 
LPDWORD lpcValues, 
LPDWORD lpcbMaxValueNameLen, 
LPDWORD lpcbMaxValueLen, 
LPDWORD lpcbSecurityDescriptor, 
PFILETIME lpftLastWriteTime);
```

- 作用

  Windows环境下，检索有关指定注册表项的信息

- 参数

  <table>
      <tr>
      	<th rowspan="2" align="center">名称</th>
          <th rowspan="2" align="center">操作</th>
          <th rowspan="2" align="center">意义</th>
          <th colspan="2" align="center">预定义</th>
      </tr>
      <tr>
      	<th align="center">值</th>
          <th align="center">意义</th>
      </tr>
      <tr>
      	<td>hkey</td>
          <td>in</td>
          <td>当前打开的键或预定义保留句柄值的句柄</td>
  <td>HKEY_CLASSES_ROOT<br/>HKEY_CURRENT_USER<br/>HKEY_LOCAL_MACHINE<br/>HKEY_USERS</td>
          <td></td>
      </tr>
      <tr>
      	<td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
      </tr>
  </table>

  
