# API docs

## Response

### OK

Wrapping "data" object

Ex.

```json
{
    "data": {/* ... */}
}
```

### Error

based [hapijs_boom_ HTTP-friendly error objects](https://github.com/hapijs/boom)

Ex.

```json
{
    "statusCode": 405,
    "error": "Method Not Allowed",
    "message": "that method is not allowed",
    /* ... */
}
```

## API

### Join & Login

### Vote

List

```json
{
    "data": {
        "contents": [
            {
                "id": 0,
                "imageUrl": "http://a.com/b.png",
                "description": "?",
                "tags": [
                    "봄 데이트",
                    "화이트 스니커즈"
                ]
            },
            {/* ... */},
            {/* ... */}
        ]
    }
}
```

Result

```json
{
    "data": {
        "id": 0,
        "result": {
            "perfect": 76,
            "man": 60,
            "woman": 40,
            "description": "20대 중반 여성이 많이 퍼펙트한 코디룩!"
        }
    }
}
```

### Challenge

```json
```

### My Page

```json
```
