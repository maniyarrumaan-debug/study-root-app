import { useState } from "react";

export default function CharteredReelsApp() { const [userId, setUserId] = useState(""); const [adminInput, setAdminInput] = useState(""); const [isAdmin, setIsAdmin] = useState(false);

const adminLogin = () => { if (adminInput === "333888") { setIsAdmin(true); localStorage.setItem("chartered_admin", "true"); } else { alert("Wrong Admin ID"); } };

const createUserId = () => { const newId = "CR-" + Math.floor(100000 + Math.random() * 900000); localStorage.setItem("chartered_user_id", newId); setUserId(newId); };

const savedId = typeof window !== "undefined" ? localStorage.getItem("chartered_user_id") : null;

if (!userId && savedId) { setUserId(savedId); }

if ( typeof window !== "undefined" && localStorage.getItem("chartered_admin") === "true" && !isAdmin ) { setIsAdmin(true); }

const reels = [ { id: 1, user: "@rumaan", caption: "Welcome to Chartered Reels 🔥", video: "https://www.w3schools.com/html/mov_bbb.mp4", likes: "12.4K", comments: "892", shares: "210", avatar: "https://i.pravatar.cc/100?img=12", }, ];

if (!userId && !isAdmin) { return ( <div className="flex min-h-screen items-center justify-center bg-black px-6 text-white"> <div className="grid w-full max-w-5xl gap-6 md:grid-cols-2"> <div className="rounded-3xl border border-white/10 bg-zinc-900 p-8 text-center shadow-2xl"> <h1 className="mb-2 text-4xl font-bold">Chartered Reels</h1> <p className="mb-8 text-zinc-400"> Login nahi hai. Har user ko ek unique ID milegi. </p>

<div className="rounded-2xl border border-white/10 bg-black p-5 mb-6">
          <p className="mb-2 text-sm text-zinc-400">New User?</p>
          <button
            onClick={createUserId}
            className="w-full rounded-2xl bg-white px-5 py-4 text-lg font-semibold text-black"
          >
            Get User ID
          </button>
        </div>
      </div>

      <div className="rounded-3xl border-2 border-red-500/40 bg-zinc-900 p-8 shadow-2xl">
        <h2 className="mb-2 text-3xl font-bold text-red-400">Admin Login</h2>
        <p className="mb-6 text-zinc-400">
          Sirf admin saare reels aur users control kar sakta hai.
        </p>

        <input
          value={adminInput}
          onChange={(e) => setAdminInput(e.target.value)}
          placeholder="Enter Admin ID"
          className="mb-4 w-full rounded-2xl border border-white/10 bg-black px-4 py-4 text-white outline-none"
        />

        <button
          onClick={adminLogin}
          className="w-full rounded-2xl bg-red-500 px-5 py-4 text-lg font-bold text-white"
        >
          Login as Admin
        </button>

        <p className="mt-4 text-xs text-zinc-500">
          Admin ID required for full control panel access.
        </p>
      </div>
    </div>
  </div>
);

}

return ( <div className="flex min-h-screen items-center justify-center bg-black px-6 text-white"> <div className="w-full max-w-md rounded-3xl border border-white/10 bg-zinc-900 p-8 text-center shadow-2xl"> <h1 className="mb-2 text-4xl font-bold">Chartered Reels</h1> <p className="mb-8 text-zinc-400"> Login nahi hai. Har user ko ek unique ID milegi. </p>

<div className="rounded-2xl bg-black p-5 border border-white/10 mb-6">
        <p className="text-sm text-zinc-400 mb-2">New User?</p>
        <button
          onClick={createUserId}
          className="w-full rounded-2xl bg-white px-5 py-4 text-lg font-semibold text-black transition hover:scale-[1.02]"
        >
          Get User ID
        </button>
      </div>

      <p className="text-xs text-zinc-500">
        ID milte hi aap automatically app use kar sakte ho, reel upload,
        comment, like sab kuch.
      </p>
    </div>
  </div>
);

}

return ( <div className="h-screen w-full overflow-y-scroll snap-y snap-mandatory bg-black text-white"> <div className="fixed left-4 top-4 z-50 flex flex-col gap-2"> {isAdmin ? ( <div className="rounded-2xl bg-red-500 px-5 py-3 text-sm font-bold text-white shadow-lg"> ADMIN MODE • ID 333888 </div> ) : ( <div className="rounded-full bg-white px-4 py-2 text-sm font-bold text-black shadow-lg"> User ID: {userId} </div> )} </div>

{reels.map((reel) => (
    <section
      key={reel.id}
      className="relative flex h-screen w-full snap-start items-center justify-center"
    >
      <video
        className="absolute inset-0 h-full w-full object-cover"
        src={reel.video}
        autoPlay
        muted
        loop
        playsInline
      />

      <div className="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-black/20" />

      <div className="absolute bottom-24 left-4 z-10 max-w-[75%]">
        <div className="mb-3 flex items-center gap-3">
          <img
            src={reel.avatar}
            alt="avatar"
            className="h-12 w-12 rounded-full border-2 border-white"
          />
          <div>
            <h2 className="text-lg font-bold">{reel.user}</h2>
            <button className="mt-1 rounded-full border border-white px-4 py-1 text-sm hover:bg-white hover:text-black">
              Follow
            </button>
          </div>
        </div>

        <p className="text-sm">{reel.caption}</p>
      </div>

      <div className="absolute bottom-28 right-4 z-10 flex flex-col items-center gap-6">
        <button className="rounded-full bg-white/20 p-3 text-2xl">❤️</button>
        <button className="rounded-full bg-white/20 p-3 text-2xl">💬</button>
        <button className="rounded-full bg-white/20 p-3 text-2xl">📤</button>
      </div>

      <nav className="absolute bottom-0 left-0 z-20 flex w-full items-center justify-around border-t border-white/10 bg-black/90 py-3">
        <button>🏠</button>
        <button>🔍</button>
        <button className="rounded-xl bg-white px-3 py-1 text-2xl text-black">
          +
        </button>
        <button>🔔</button>
        <button>👤</button>
      </nav>
    </section>
  ))}
</div>

); }
