

#  Manufacturing Quality Control Using SQL – Finding the Flaws Before They Fail Us

There’s something fascinating about how a tiny variation in a machine part can snowball into a major issue. I wanted to explore that — not just from an engineer’s perspective, but from a data analyst’s lens.

This project is where **manufacturing meets SQL** — and where data helps keep quality in check.

---

##  Why I Did This

I’ve always been curious about how production floors maintain consistency. How do they catch parts that don’t meet the mark? Can data tell us *before* something goes wrong?

So I challenged myself with a simple goal:  
**Use SQL to simulate a live quality control system** that tracks, monitors, and flags manufacturing issues — just like a plant floor would.

No flashy tools. No dashboards. Just logic, data, and SQL.

---

##  What the Data Revealed

###  Every Operator Tells a Story  
Some operators produced consistently within range — calm and steady. Others? Small spikes, unexpected dips. It felt like reading between the lines of their shift logs.

###  Patterns Before Problems  
By building a rolling average and control limits, I started to *see* the process shifting — parts slowly creeping out of spec. It wasn’t dramatic, but it was real. And it mattered.

###  SQL as the Early Warning System  
What felt the most exciting was using **just SQL** to surface insights that might normally get buried.  
No fancy tools — just queries that whispered, “Hey, something’s off here.”

---

##  About the Dataset

I worked with a simple CSV file (`parts.csv`) that included:
- `item_no`: the sequence of production
- `operator`: who handled it
- `height`: the critical dimension we’re monitoring

It looked basic. But behind it was a full story waiting to be told — of quality, precision, and control.

---

##  What I Used

- **SQL**: Core engine behind the analysis
- **Window functions**: To simulate rolling observations (like a moving inspection window)
- **Control limits logic**: Inspired by SPC (Statistical Process Control)
- **Excel**: For reviewing output and double-checking trends
- **Notebook (optional)**: Just to validate that my logic worked

---

##  What I Learned

- Data can whisper before it screams — if we know how to listen.
- Control charts aren’t just theory — they can live inside your SQL.
- Even a simple file of part measurements can unlock deep insights about process stability and operator behavior.
- The best part? You don’t always need big tools. Sometimes, SQL is enough.

---

##  Let’s Talk

If you’re someone who loves building things that *catch problems before they break something*, or if you're into applying SQL to real-world operational problems — I’d love to connect.

Let’s make data not just informative, but **protective**.
