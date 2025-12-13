function showFaucet() {
  loginPage.classList.add("hidden");
  registerPage.classList.add("hidden");
  faucetPage.classList.remove("hidden");

  const email = getLoggedIn();
  const users = getUsers();
  const user = users[email];

  // Contar referidos
  let referidos = Object.values(users).filter(u => u.referido === email).length;
  let bonusReferidos = referidos * 5; // cada referido da 5 monedas de bonus

  message.innerHTML = `
    Balance: ${user.balance} monedas<br>
    Referidos: ${referidos} (Bonus recibido: ${bonusReferidos} monedas)
  `;

  // Mostrar cooldown si existe
  let userCooldown = getCooldown(email);
  if (userCooldown > 0) {
    claimButton.disabled = true;
    claimButton.classList.add("opacity-50", "cursor-not-allowed");
    timerDisplay.textContent = formatTime(userCooldown);
    startCooldown(email);
  } else {
    timerDisplay.textContent = formatTime(cooldown);
    claimButton.disabled = false;
    claimButton.classList.remove("opacity-50", "cursor-not-allowed");
  }
}