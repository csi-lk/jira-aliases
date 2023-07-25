# Jira Aliases

Aliases and helpers for many jira related tasks to speed up my workflow

## Usage

```bash
ja » simple jira aliases by Callum Silcock

ja c               | create ticket
ja o  <?ticket>    | open ticket
ja mt <?ticket>    | move ticket to 'todo'
ja mp <?ticket>    | move ticket to 'in progress'
ja mr <?ticket>    | move ticket to 'review'
ja md <?ticket>    | move ticket to 'done'
ja f  <?ticket>    | focus on ticket
ja z  <?commands>  | combine multiple single commands together
```

`?ticket` will always fall back to your previously created ticket

## Installation

### Linux / OSX

Make sure curl is installed

#### Automagic (recommended)

```bash
curl -fsSL https://raw.githubusercontent.com/csi-lk/jira-aliases/master/install | bash
```

#### Manual

Clone the repo and

```bash
git clone git@github.com:csi-lk/jira-aliases.git
sudo chmod -v +x jira-aliases/bin/ja
sudo cp jira-aliases/bin/ja /usr/local/bin/ja
ja -V
```

### Windows

Open a prompt and navigate to a folder included in your `PATH`.

```bash
powershell -Command "(New-Object Net.WebClient).DownloadFile('https://raw.githubusercontent.com/csi-lk/jira-aliases/master/bin/ja', 'ja')"
powershell -Command "(New-Object Net.WebClient).DownloadFile('https://raw.githubusercontent.com/csi-lk/jira-aliases/master/bin/ja.cmd', 'ja.cmd')"
```

Open a new prompt and everything should work

---

🧔 Be sure to checkout [my other repos](https://github.com/csi-lk/) and [website / blog](https://csi.lk)
