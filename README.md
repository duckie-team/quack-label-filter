# quack-label-filter-actions

꽥꽥 배포용으로 사용되는 label 필터링 액션

---

```yaml
inputs:
  labels:
    description: '해당 PR 에 설정된 label'
    required: true

outputs:
  bump_type:
    description: 'Bump 할 버전'
  release_target:
    description: 'Release 할 대상'
  publish_module_id:
    description: 'Publish 할 모듈명'
  is_snapshot:
    description: '스냅샷 배포인지 여부'
```