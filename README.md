[package.json](https://github.com/user-attachments/files/24714356/package.json)

{
  "name": "zenhub",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "14.1.0",[create-checkout-session.js](https://github.com/user-attachments/files/24714372/create-checkout-session.js)

export default function handler(req, res) {
  res.status(200).json({ ok: true });
}

    "react": "18.2.0",
    "react-dom": "18.2.0"
  }
}[index.js](https://github.com/user-attachments/files/24714370/index.js)

export default function Home() {
  return (
    <div style={{fontFamily:'sans-serif',padding:'40px',textAlign:'center'}}>
      <img src="/logo.png" width="96" height="96" style={{borderRadius:20}} />
      <h1 style={{color:'#047857'}}>ZenHub</h1>
      <p>Game performance playbooks. Calm focus. Consistent results.</p>
      <h2>NBA 2K26 Bundle – $25</h2>
      <p>Includes 5 performance scripts focused on rhythm, decision-making, and composure.</p>
      <button style={{padding:'12px 20px',borderRadius:12,background:'#059669',color:'#fff',border:'none'}}>
        Buy Bundle – $25
      </button>
    </div>
  )
}

