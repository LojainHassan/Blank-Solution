# Blank-Solution
Blank Solution added Library , many Console App

#How to add many project in same solution
1)Add ProjectReference to project

  <ItemGroup>
    <ProjectReference Include="..\Solution1.Hr\Solution1.Hr.csproj" />
  </ItemGroup>
## .. this two point mean relativePath
Solution1.Project1 is referencing to Solution1.Hr

2) Check access Modifier
what if the different between app and Library
app able to communicate with user and it has UI 
