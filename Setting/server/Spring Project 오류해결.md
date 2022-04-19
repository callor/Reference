# Spring Project 오류해결
## Deployment Assembly 메뉴가 사라졌을 경우
* project 폴더의 .project 파일을 열고, ```<nature>``` 설정을 찾는다
```
	<natures>
		<nature>org.springframework.ide.eclipse.core.springnature</nature>
		<nature>org.eclipse.jdt.core.javanature</nature>
		<nature>org.eclipse.m2e.core.maven2Nature</nature>
		<nature>org.eclipse.wst.common.project.facet.core.nature</nature>
	</natures>
```

		
* 다음과 같이 ```<nature>org.eclipse.wst.common.modulecore.ModuleCoreNature</nature>``` 를 추가한다

```
	<natures>
		<nature>org.springframework.ide.eclipse.core.springnature</nature>
		<nature>org.eclipse.jdt.core.javanature</nature>
		<nature>org.eclipse.m2e.core.maven2Nature</nature>
		<nature>org.eclipse.wst.common.project.facet.core.nature</nature>
		<nature>org.eclipse.wst.common.modulecore.ModuleCoreNature</nature>
	</natures>
```