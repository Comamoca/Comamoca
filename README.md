<p align="left"> 
  <a href="https://github.com/Comamoca/yutkat/">
    <img src="https://komarev.com/ghpvc/?username=Comamoca" alt="yutkat" />
  </a>
  <a href="http://twitter.com/comacoma_san">
    <img height="20" src="https://img.shields.io/twitter/follow/comacoma_san?label=Twitter&logo=twitter&style=flat" />
  </a>
  <a href="https://github.com/Comamoca">
    <img height="20" src="https://img.shields.io/github/followers/Comamoca?label=follow&logo=github&style=flat" />
  </a>
  <a href="https://www.reddit.com/user/Comamoca">
    <img height="20" src="https://img.shields.io/reddit/user-karma/combined/Comamoca?label=Reddit&logo=reddit&style=flat" />
  </a>
  <a href="http://qiita.com/Comamoca">
    <img height="20" src="https://qiita-badge.apiapi.app/s/Comamoca/posts.svg" />
  </a>
  <//qiita.com/Comamoca">
    <img height="20" src="https://qiita-badge.apiapi.app/s/Comamoca/contributions.svg" />
  </a>
</p>

[![Comamoca's GitHub stats](https://github-readme-stats.vercel.app/api?username=Comamoca)](https://github.com/Comamoca/github-readme-stats)

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.gnu.org/software/bash/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>


# Hi, my name is Coma. 👋
# Welcome to Coma profele!☕


## ⚙Development Environment

- Manjaro Linux (LXDE)
- [Neovim](https://github.com/neovim/neovim)

## 🌱 I’m currently learning ...

- [Neovim](https://github.com/neovim/neovim)
- [Python Neovim cliant](https://github.com/neovim/pynvim)
- [Go](https://github.com/golang/go)
" Change denite default options
call "#option('default', {
    'split': 'floating',
    'winwidth': float2nr(&columns * s:denite_win_width_percent),
    'wincol': float2nr((&columns - (&columns * s:denite_win_width_percent)) / 2),
    'winheight': float2nr(&lines * s:denite_win_height_percent),
    'winrow': float2nr((&lines - (&lines * s:denite_win_height_percent)) / 2),
    })

" Define mappings
autocmd FileType denite call s:denite_my_settings()
function! s:denite_my_settings() abort
  nnoremap <silent><buffer><expr> <CR>
   denite#do_map('do_action')
  nnoremap <silent><buffer><expr> d
   denite#do_map('do_action', 'delete')
  nnoremap <silent><buffer><expr> p
   denite#do_map('do_action', 'preview')
  nnoremap <silent><buffer><expr> q
   denite#do_map('quit')
  nnoremap <silent><buffer><expr> i
   denite#do_map('open_filter_buffer')
  nnoremap <silent><buffer><expr> <Space>
   denite#do_map('toggle_select').'j'
endfunction

" フィルタバッファで <CR> すると候補を実行する
    inoremap <silent><buffer> <CR> <Esc>
       :call denite#move_to_parent()<CR>
       <CR>
- [Rust](https://github.com/rust-lang/rust)

## 🔭 I’m currently working on ... 

- Not yet...

## 👯 I’m looking to collaborate on ...

- Not yet...


## 💬 Ask me about ...

I'm a high school student and I'm developing a plugin for Vim.
I am also a member of a group called [Ablaze](https://github.com/Ablaze-MIRAI).

I love [Anime]() and [hololive]()!


## 📫 How to reach me ...

- [Twitter](https://twitter.com/comacoma_san)
- [email](amagaeru.dev@gmail.com)


## ⚡ Fun fact ... 

Favorite foods are ramen, curry,
I like ramen🍜, curry🍛, and sushi🍣.

And as for sweets, I like macaroons and monaka. 

<!-- **Comamoca/Comamoca** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile. -->
<!--  -->
<!-- Here are some ideas to get you started: -->
<!--  -->
<!-- - 🔭 I’m currently working on ... -->
<!-- - 🌱 I’m currently learning ... -->
<!-- - 👯 I’m looking to collaborate on ... -->
<!-- - 🤔 I’m looking for help with ... -->
<!-- - 💬 Ask me about ... -->
<!-- - 📫 How to reach me ... -->
<!-- - 😄 Pronouns: ... -->
<!-- - ⚡ Fun fact: ... -->
