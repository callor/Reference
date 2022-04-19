# Spring Project 오류해결

## ```org.apache.catalina.LifecycleException, java.lang.ClassNotFoundException```
* ```property / Deployment Assembly / Add / Java Build Path Entries / Maven...``` 선택하여 추가
* ```java facets``` 복구
* clean / 재시작

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

* 프로젝트를 ```delete``` 이때 Disk 에서 삭제 항목을 체크하지 않는다
* 다시 프로젝트 ```import```