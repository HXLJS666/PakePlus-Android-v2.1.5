# 欢迎使用你的秒哒应用代码包
秒哒应用链接
    URL:https://www.miaoda.cn/projects/app-8i2rrxetslc1

# 音效文件说明

本目录用于存放游戏所需的所有音效文件。

## 所需音效文件列表

### 音效 (SFX)

1. **gunshot.mp3** - 枪声
   - 触发时机：玩家射击时
   - 建议时长：0.1-0.3秒
   - 音量：中等

2. **player-hurt.mp3** - 玩家受伤
   - 触发时机：玩家被僵尸攻击时
   - 建议时长：0.2-0.5秒
   - 音量：中等偏高

3. **zombie-hurt.mp3** - 僵尸受伤
   - 触发时机：僵尸被子弹击中时
   - 建议时长：0.1-0.3秒
   - 音量：中等偏低

4. **zombie-death.mp3** - 僵尸死亡
   - 触发时机：僵尸死亡时
   - 建议时长：0.3-0.8秒
   - 音量：中等

5. **zombie-explosion.mp3** - 爆炸僵尸爆炸
   - 触发时机：爆炸僵尸死亡时
   - 建议时长：0.5-1.0秒
   - 音量：中等偏高

### 背景音乐 (BGM)

6. **menu-bgm.mp3** - 开始界面背景音乐
   - 播放时机：主菜单界面
   - 循环播放：是
   - 音量：较低

7. **game-bgm.mp3** - 游戏时背景音乐
   - 播放时机：游戏进行中
   - 循环播放：是
   - 音量：较低

8. **gameover-bgm.mp3** - 游戏结束背景音乐
   - 播放时机：游戏结束界面
   - 循环播放：是
   - 音量：较低

## 音效格式要求

- **格式**：MP3（推荐）或 OGG
- **采样率**：44.1kHz 或 48kHz
- **比特率**：128kbps - 192kbps
- **声道**：单声道或立体声

## 音效来源建议

### 免费音效资源网站

1. **Freesound.org** - https://freesound.org/
2. **Zapsplat** - https://www.zapsplat.com/
3. **Mixkit** - https://mixkit.co/free-sound-effects/
4. **OpenGameArt** - https://opengameart.org/

### 音效生成工具

1. **SFXR** - 8位风格音效生成器
2. **ChipTone** - 复古游戏音效生成器
3. **Audacity** - 音频编辑软件

## 临时占位

如果暂时没有音效文件，系统会优雅地处理（不会报错），但建议尽快添加音效以提升游戏体验。

## 更改音效

如需更改音效文件路径或设置，请编辑：
`src/config/audioConfig.ts`

