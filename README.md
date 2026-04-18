<div align="center">

# 🦝 Artyom Tuzov

**`CV/ML Engineer · Robotics Software · Innopolis`**

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/artyomzifir)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a.tuzov.work@mail.ru)
[![CV EN](https://img.shields.io/badge/CV%20EN-4CAF50?style=for-the-badge&logo=read-the-docs&logoColor=white)](https://rxresu.me/artem.a.tuzov/git-en)
[![CV RU](https://img.shields.io/badge/CV%20RU-4CAF50?style=for-the-badge&logo=read-the-docs&logoColor=white)](https://rxresu.me/artem.a.tuzov/git-ru)
[![VK](https://img.shields.io/badge/VK-0077FF?style=for-the-badge&logo=vk&logoColor=white)](https://vk.ru/artyomzifir)
[![Bluesky](https://img.shields.io/badge/Bluesky-0285FF?style=for-the-badge&logo=bluesky&logoColor=white)](https://bsky.app/profile/artyomzifir.bsky.social)

</div>

---

```python
#!/usr/bin/env python3
import rclpy
from rclpy.node import Node
from std_msgs.msg import String

class ArtyomTuzov(Node):
    def __init__(self):
        super().__init__('artyom_tuzov')

        self.stack = {
            'perception':  ['YOLO11', 'ONNX Runtime', 'OpenCV', 'PyTorch'],
            'robotics':    ['ROS2', 'BehaviorTree', 'MAPF', 'Gazebo'],
            'languages':   ['Python', 'C++'],
            'hw':          ['Jetson', 'Unitree', 'Raspberry'],
        }

        self.achievements = [
            '🥇 1st place — Russian Championship in Robotics Programming (2025)',
            '🥈 2nd place — Tenderhack (2026)',
            '📍 Top-150 — Yandex ML-Run',
        ]

        self.current = [
            'Multi-agent swarm: LLM -> BehaviorTree -> ROS2',
        ]

        self.declare_parameter('status', 'open_to_hire')
        self.get_logger().info('Perception online. Ready to ship. 🦝')

if __name__ == '__main__':
    rclpy.init()
    rclpy.spin(ArtyomTuzov())
```

---
