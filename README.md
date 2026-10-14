# RecordAudioMix

## EN

A simple GNU/Linux bash script to record audio input and a mix of system audio and audio input simultaneously. The audio in the mix stays in sync and gets normalized in the end. This is especially useful to check your progress during language shadowing practice, for example, in Refold.

### Dependencies:

- PipeWire audio subsystem for sound recording via pw-record.
- ffmpeg for mixing and encoding the recorded audio.

### Preparation Guide:

1. Copy the record_audio_mix script into a directory under [PATH](https://www.digitalocean.com/community/tutorials/how-to-view-and-update-the-linux-path-environment-variable).

2. Mark the script as executable via file manager or terminal (e.g. `chmod +x ./record_audio_mix`).

3. Assign a certain shortcut (e.g. Alt+Super+a) to record audio with the script in your system settings or configuration. For example:

<img width="639" height="221" alt="image" src="https://github.com/user-attachments/assets/c2863237-623e-4372-80d1-79cfd43aa4dd" />


### Use Guide:

1. Press the assigned shortcut in order to start recording the audio input and the mix of system audio and audio input simultaneously.
2. Play your audio and speak into the input device.
3. Press the shortcut again to stop the recording.
4. Find the recorded files in the Downloads directory.

## UA

Простий GNU/Linux bash-скрипт для одночасного запису аудіовходу та міксу системного аудіо й аудіовходу. Аудіо в міксі залишається синхронізованим і наприкінці нормалізується. Це особливо корисно для відстеження прогресу під час практики наслідування мови, наприклад, в Refold.

### Залежності:

- Аудіо підсистема PipeWire для запису звуку через pw-record.
- ffmpeg для змішування та кодування записаного аудіо.

### Інструкція з підготовки:

1. Скопіюйте скрипт record_audio_mix у директорію, що входить до [PATH](https://itmaster.biz.ua/programming/linux/path-in-linux.html).

2. Зробіть скрипт виконуваним через файловий менеджер або термінал (наприклад, `chmod +x ./record_audio_mix`).

3. Призначте певну комбінацію клавіш (наприклад, Alt+Super+a) для запису аудіо за допомогою скрипта в налаштуваннях або конфігурації системи. Наприклад:

<img width="639" height="221" alt="image" src="https://github.com/user-attachments/assets/c2863237-623e-4372-80d1-79cfd43aa4dd" />

### Інструкція з використання:

1. Натисніть призначену комбінацію клавіш, щоб розпочати одночасний запис аудіовходу та міксу системного аудіо й аудіовходу.
2. Запустіть відтворення аудіо та говоріть у пристрій вводу.
3. Натисніть комбінацію клавіш ще раз, щоб зупинити запис.
4. Знайдіть записані файли у директорії Завантаження.
