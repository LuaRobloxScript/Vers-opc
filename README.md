-- Função de Notify estilo WindUI
local function Notify(title, text, duration)
    game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = title;
        Text = text;
        Duration = duration or 5;
    })
end

-- Mensagem que você pediu
Notify(
    "⚠️ WindUI",
    "Script desatualizado!\nNova versão adicionada\n(Adicionado ESP estilo Free Fire hacker 🔥)",
    7
)
