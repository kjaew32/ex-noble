insert bookmark lit

javascript:(async()=>{
  let scriptUrl = "https://raw.githubusercontent.com/username/repository-name/main/index.js"; // GitHub Raw URL
  let scriptRes = await fetch(scriptUrl);
  let scriptText = await scriptRes.text();
  eval(scriptText);
})();
