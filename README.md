<div align="center">
    <br>
    <p align="center">
        <img width="128" src="./app-icon.png" alt="Amazuki Icon">
    </p>
    <h1 align="center">Amazuki</h1>
    <h2 align="center">雨月</h1>
    <p align="center">
        <a href="https://github.com/TouhouAsia/Amazuki">
            <img alt="Watchers" src="https://img.shields.io/github/watchers/TouhouAsia/Amazuki?style=for-the-badge&logo=github&color=ff69b4&logoColor=fff&labelColor=333"></a>
        <a href="https://github.com/TouhouAsia/Amazuki/issues">
        <img alt="Issues" src="https://img.shields.io/github/issues/TouhouAsia/Amazuki?style=for-the-badge&logo=gitbook&color=yellow&logoColor=fff&labelColor=333"></a>
        <a href="https://github.com/TouhouAsia/Amazuki/stargazers">
        <img alt="Stargazers" src="https://img.shields.io/github/stars/TouhouAsia/Amazuki?style=for-the-badge&logo=starship&color=blueviolet&logoColor=fff&labelColor=333"></a>
        <a href="https://github.com/TouhouAsia/Amazuki/forks">
        <img alt="Fork" src="https://img.shields.io/github/forks/TouhouAsia/Amazuki?style=for-the-badge&logo=forgejo&color=green&logoColor=fff&labelColor=333"/></a>
    </p>
</div>

## 构建步骤

1. **安装 Bun:**
   ```shell
   curl -fsSL https://bun.sh/install | bash
   ```

2. **安装 Rustup:**
   ```shell
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```

3. **安装 Tauri CLI:**
   ```shell
   cargo install tauri-cli
   ```

4. **安装项目依赖:**
   ```shell
   bun install
   ```

5. **构建应用:**
   ```shell
   cargo tauri build
   ```
