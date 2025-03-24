
# 👋 Hi, I'm [thashimo]
### 42Tokyo Student & Passionate Developer

[![42 Profile](https://img.shields.io/badge/42-Profile-000000?style=flat&logo=42)](https://profile.intra.42.fr/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yourprofile/)

---

## 🏫 42Tokyo Curriculum Journey

**Peer-to-Peer Learning | Project-Based Curriculum | Intensive Coding Experience**

```c
#include <stdio.h>

int main(){
    printf("Born2code\n");
    return 42;
}
```

### 📚 Curriculum Overview
| Category          | Key Projects                      | Skills Acquired                  |
|-------------------|-----------------------------------|-----------------------------------|
| Core Curriculum   | Libft, ft_printf, get_next_line   | C Programming, Algorithms         |
| Graphics          | so_long            | GameProgramming, 3D Rendering, Mathematics         |
| System Programming| born2beroot, pipex, minishell, philo     | UNIX System, Multithreading       |
| Web & Mobile      | Not yet          | Docker, Kubernetes, C++           |

---

1. コアカリキュラム (Core Curriculum)

プロジェクト例: Libft, ft_printf, get_next_line, pushswap

習得スキル:

Cプログラミング: メモリ管理やポインタ操作、文字列処理などの基礎的なスキルを学びました。両端キューなどのデータ構造を自作し、その中で命令を実行し、最小の数でソートを実行するアルゴリズムを実装しました。

アルゴリズム: 効率的なデータ処理やソートアルゴリズムの実装を通じて、アルゴリズム設計の基礎を学びました。

標準ライブラリの実装: ft_printf(printfの再実装)やget_next_line(readlineの再実装)などの関数を自作し、標準ライブラリの理解を深めました。

2. グラフィックス (Graphics)

プロジェクト例: so_long

習得スキル:

ゲームプログラミング: 2Dゲームの制作を通じて、ゲームのロジックやキャラクターの動き、イベント処理を実装しました。シグナルを適切に設定し、終了時にはメモリを解放する処理を実装しています。

マップの検証: ゲーム内でのマップが有効なものか調べる際に幅優先探索などのアルゴリズムを実装しました。


3. システムプログラミング (System Programming)

プロジェクト例: born2beroot, pipex, minishell, philo

習得スキル:

UNIXシステム: virtualboxを使用した、DebianOSのインストール、ポートなどのネットワーク設定やセキュリティ設定を行いました。また、シェルやプロセス管理を自作することで、UNIX環境でのプロセス制御、ファイル操作、シグナル処理などの基礎を学びました。

マルチスレッド処理: philoプロジェクトでは、スレッドを使って並列処理を実装し、競合状態や同期の問題に対処しました。

低レベルのI/O操作: ファイルディスクリプタやパイプ、シグナルなど、OSと直接やり取りする方法を学びました。

メモリ管理: 動的メモリの確保と解放を適切に行い、メモリリークを避けるためにValgrindを使用しました。


## 🛠 Technical Arsenal

### Programming Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Shell_Script-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Tools & Technologies
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Vim](https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white)


## 🚀 Notable Projects

### 1. **minishell** [![C](https://img.shields.io/badge/C-100%25-success)]()
**Key Features**:
- 🛠 Pipe chaining (`|`) and IO redirections (`>`, `>>`, `<`)
- 📟 Signal handling for Ctrl-C/Ctrl-D/Ctrl-\\
- 🧩 Built-in commands (echo, cd, pwd, export, unset, env, exit)
- Collaborated with other students, leveraging Git for version control and improving teamwork and development skills.

Unix シェルの基本機能を再現した軽量なシェルプログラムです。C言語を用いてゼロから実装し、シェルの仕組みを理解しながら、プロセス管理やパイプ処理などの低レベルなシステムプログラミングを学ぶことを目的としました。また今回、標準で実装されている関数も学習目的で敢えて自作のものを使っております。もちろん終了時、実行時にメモリリークは起きないよう、Valgrindなどのツールを使用してチェックしております。
このプロジェクトは2人で進めたため、モジュール化を徹底し、コマンド実行部分、Parser部分、Tokenizer部分に大きく分け、作業を分担しました。
AST（抽象構文木）を用いた構造的なパーシングを導入し、複雑なコマンド入力に耐えられるようにしています。

---
[![Demo](https://img.shields.io/badge/View_Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/demo-link)

## 📈 GitHub Stats

<div align="left">
  <p> 
    <img alt="Top Langs" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tac4720&layout=compact&show_icons=true&theme=tokyonight" />
    <img alt="github stats" height="195px" src="https://github-readme-stats.vercel.app/api?username=tac472&heme=tokyonight&show_icons=ture" />
  </p>
  <p>
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=tac4720&theme=tokyonight" width="810px">
  </p>
</div>
---
