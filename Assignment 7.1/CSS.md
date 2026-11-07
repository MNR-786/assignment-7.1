* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  color: #203047;
  background: #f5f8fc;
}

.site-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
  padding: 18px 6%;
  background: #ffffff;
  border-bottom: 1px solid #dce4ed;
}

.logo {
  color: #203047;
  font-size: 1.4rem;
  font-weight: bold;
  text-decoration: none;
  white-space: nowrap;
}

.logo span {
  color: #2877b8;
}

.main-nav {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 24px;
}

.main-nav a {
  color: #40546a;
  text-decoration: none;
}

.main-nav a:hover {
  color: #2877b8;
}

.header-button {
  padding: 10px 16px;
  border-radius: 7px;
  background: #2877b8;
  color: #ffffff;
  font-weight: bold;
  text-decoration: none;
  white-space: nowrap;
}

.header-button:hover {
  background: #1d5e94;
}

main {
  padding: 60px 6%;
  text-align: center;
}

@media (max-width: 650px) {
  .site-header {
    flex-wrap: wrap;
    justify-content: center;
  }

  .main-nav {
    order: 3;
    width: 100%;
    flex-wrap: wrap;
    gap: 14px 20px;
  }
}