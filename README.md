# qslElixir
QSL card repository for Elixir treatment

--general about--

--steps--

1. create new repository
  a. title it qslElixir
  b. <control-v> green code button dropdown menu and
  c. paste into terminal window
  
  A. (side-quest)
    1. establish working directory under QSL>First Try> qslElixir 
    2. utilize "command-shift-." to locate hidden files within the existing .git file
    3. in terminal, prompt "echo $PS1"
    4. change "\h: \w \u\$" to "PS1='\w \$'"
    5. note $ response to "pwd" prompt in terminal--we have established a new baseline
    6. At "$", prompt "cd QSL" then ls into First Try. 
    7. locate ".bash_profile"
    8. add ".DS_store" to address compatability between MAC and Windows
    9. Push on GitHub
      9a. Prompt with log in info for GitHub
      9b. Note that user name is supplanted by computer user name
      
 2. Homebrew/Elixir Install
  a. install homebrew if not already on mac
      https://brew.sh/
  b. use brew to install elixir
    https://elixir-lang.org/install.html
  c. brew update
  d. brew install elixir
  e. should install erlang as well
  f. install phoenix
  g. mix local.hex
  h. mix archive.install hex phx_new 1.5.7
  i. install node.js https://nodejs.org/en/download/
  j.brew install node
  
 3. For Next Time
  install postgreSQL https://wiki.postgresql.org/wiki/Detailed_installation_guides
