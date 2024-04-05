```python
import github

class mciem(github.Profile):
    def __init__(this):
        super().__init__()
        
        this.name = "mciem"
        this.age  = 15

        this.socials = {
            "discord": "mciemmmmmmmmmm",
            "telegram": "@mciem1"
        }

    def get_open_source_projects(this):
        return github.get(
            url=this.name,
            params={
                "tab": "repositories"
            }
        )
        
```
