# Sistem Pengurusan NGO IKRAM

The portal through which IKRAM manages its organisation — the ahli it is made of, the jawatankuasa that run it, its kewangan, and its usrah. One portal, many modules, shared vocabulary.

The interface is in Bahasa Melayu. Domain terms stay in Bahasa Melayu in code as well as in the UI: `ahli`, `usrah`, `kepakaran` and the rest carry meaning that no English translation preserves, so translating them costs precision.

## Language

### Organisation

**Peringkat**:
A tier of the organisation. There are exactly three: Pusat, Negeri, Kawasan.
_Avoid_: Level, tier, org unit

**Pusat**:
The national tier — the whole of IKRAM. There is exactly one.

**Negeri**:
A state tier, belonging to Pusat.

**Kawasan**:
The local tier, belonging to a Negeri. The tier at which most ahli are organised.
_Avoid_: Branch, chapter, area

**Jawatankuasa**:
A committee that governs at a given peringkat, and the body whose mesyuarat the portal records.
_Avoid_: Committee, board, JK

### People

**Ahli**:
A member of IKRAM. Belongs to one Kawasan and is identified by a Nombor Ahli.
_Avoid_: Member, user, person

**Nombor Ahli**:
The identifier IKRAM assigns to an ahli. The ahli's identity throughout the portal.
_Avoid_: Member ID, membership number

**Pengurusan**:
The ahli who hold office at a peringkat and administer the portal. The only people who log in — an ahli who is not pengurusan is a record in the portal, not a user of it.
_Avoid_: Admin, staff, officer

**Kepakaran**:
An area of skill or professional expertise an ahli has, recorded so that other ahli can be found by it. The portal presents kepakaran as a directory — something to browse and search, not to match or assign against.
_Avoid_: Skill, expertise, specialisation, tag

### Activity

**Usrah**:
A small recurring circle of ahli who meet weekly. What the rancangan usrah mingguan plans.
_Avoid_: Study group, circle, cell

**Mesyuarat**:
A convened sitting of a jawatankuasa, with its agenda, attendance and minutes.
_Avoid_: Meeting, session
