<header>
    <img class="page-cover-image" src="https://www.notion.so/images/page-cover/rijksmuseum_claesz_1628.jpg" style="object-position: center 100%;" />
    <h1 class="page-title">📋 LeetCode NoteBook</h1>
</header>

<table>
    <thead>
        <tr>
         <th>题号</th>
         <th>题目</th>
         <th>解题思路&重点</th>
         <th>Tips</th>
         <th>主题</th>
         <th>难度</th>
         <th>链接</th>
      </tr>
    </thead>
    <tbody>
      <tr>
         <td>#695</td>
         <td>Max Area of Island</td>
         <td class="cell-!wf;">
            <strong>- How to mark the island that has been visited?</strong> - set the value of island <code>0</code>
            </br>
            </br>
            <strong>- When to end the BFS?</strong>
            - exceed the boundary. - the target is nor an island. - the target is an island but has been visited.
        </td>
        <td class="cell-gV@O">
            <strong>- Problems:</strong>
            </br>
            - The return value is the maximum area of island, not the number of islands.
            </br>
            - Need to use a global variable <code>area</code> to store each area of island, but a local variable in the
            <code>dfs()</code> method, which will lead to lost area data when ending the current recursion.
        </td>
         <td></td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
      </tr>
   </tbody>
</table>


