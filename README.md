# UDiscord Bot
이 플러그인은 디스코드 웹 훅을 사용하여 디스코드 알림 메세지를 전달합니다.

# Install
유니티 패키지 매니저에서 +버튼을 누르고 Add Package Git URL을 선택하여 `https://github.com/NK-Studio/UDiscod-Bot`을 추가합니다.

# 사용 방법
``` C#
DiscordBot
    .Create(
        "디스코드 웹 훅")
    .WithContent("메세지")
    .AddEmbed(
        Embed
            .Create()
            .WithTitle("임베드 메세지 제목")
            .WithDescription("임베드 메세지 내용")
            .SetColor(Color.red) // 왼쪽 선 색상
    )
    .Send();
```
