# f1-spint
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no, viewport-fit=cover">
<title>Шашечный спринт — Формула-1</title>
<meta name="description" content="Мини-гонка Формулы-1 до клетчатого флага">
<meta name="theme-color" content="#111114">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="F1 Спринт">
<link rel="manifest" href="data:application/manifest+json;charset=utf-8,%7B%22name%22%3A%20%22%D0%A8%D0%B0%D1%88%D0%B5%D1%87%D0%BD%D1%8B%D0%B9%20%D1%81%D0%BF%D1%80%D0%B8%D0%BD%D1%82%20%E2%80%94%20%D0%A4%D0%BE%D1%80%D0%BC%D1%83%D0%BB%D0%B0-1%22%2C%20%22short_name%22%3A%20%22F1%20%D0%A1%D0%BF%D1%80%D0%B8%D0%BD%D1%82%22%2C%20%22description%22%3A%20%22%D0%9C%D0%B8%D0%BD%D0%B8-%D0%B3%D0%BE%D0%BD%D0%BA%D0%B0%20%D0%A4%D0%BE%D1%80%D0%BC%D1%83%D0%BB%D1%8B-1%20%D0%B4%D0%BE%20%D0%BA%D0%BB%D0%B5%D1%82%D1%87%D0%B0%D1%82%D0%BE%D0%B3%D0%BE%20%D1%84%D0%BB%D0%B0%D0%B3%D0%B0%22%2C%20%22start_url%22%3A%20%22.%22%2C%20%22scope%22%3A%20%22.%22%2C%20%22display%22%3A%20%22standalone%22%2C%20%22orientation%22%3A%20%22portrait%22%2C%20%22background_color%22%3A%20%22%23ffffff%22%2C%20%22theme_color%22%3A%20%22%23111114%22%2C%20%22icons%22%3A%20%5B%7B%22src%22%3A%20%22data%3Aimage/png%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAgAAAAIACAIAAAB7GkOtAAAJfUlEQVR4nO3dsU5cVxRAURP5CxjJdK6dIlX%2Bv3eTKkW%2BgWJK16RAcoOCCczMve/steoEDnrS2fc%2BNPju/v7Lp7Dz%2BXH1CCudTg%2BrR1jJ0189wkrxp//st9UDALCGAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAETdPT09rZ5hpdPpYfUIK53Pj6tHWMnTXz3CSp7%2BJzcAgCwBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiLq7v/%2ByeoaVzufH1SOsdDo9rB5hJU9/9QgrxZ/%2BMzcAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiLp7enpaPcNKp9PD6hFWOp8fV4%2Bwkqe/eoSVPP1PbgAAWQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQdXd//2X1DCudz4%2BrR1jpdHpYPcJKnv7qEVaKP/1nbgAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFF3P378WD0DAAu4AQBECQBAlAAARAkAQJQAAEQJAECUAABECQBA1N33r99WzwDAAm4AAFECABAlAABRAgAQJQAAUQIAECUAAFGfVw8AN/XHP3%2B9/h/8/fuft5kElvNBMOb75dL/L2LAbALAWO/e%2By8pASMJANNccO%2B/pARM4pfAjHLV7X%2BDrw%2B35AbAEDdeza4CDOAGwAS3P5i7CjCAGwDHtnwRuwpwXG4AHNjy7b/JDPA%2BAsBR7bN595kE/hcB4JB227m7zQNvIQAcz57bds%2Bp4BUCwMHsvGd3ng1eEgCOZP8Nu/%2BE8JMAAEQJAIdxlMP1UeYEAeAYjrVVjzUtWf5BGHJe%2BeyuxU2KPwXBAVxqL7/xzzbc%2BNvBKgLA7i6yjt%2Bxi1d9X7gZr4AY7t0r%2BPl/9FKIwfwSmMk%2BfgB3hGcwAWBrHzmAX2p3f%2BTruECwMwFgpsue3N0DGEkAGOga%2B1oDmEcA2NeM9yczfgpGEgCmud5R3SWAYQQAIEoAGOXah3SXACYRADY16dX5pJ%2BFSQSAOW5zPHcJYAwBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAWCO23zg1sd6GUMA2NSkD9xO%2BlmYRAAY5drHc8d/JhEAgCgBYJrrHdId/xlGANjXjFfnM34KRhIABrrGUd3xn3kEgJkuu69tf0YSALb2kfcnl9raH/k63v%2BwMwFgso83wNmfwT6vHgCu63mDv%2BMkbvUz3t33r99WzwC/cKld/MYM3PjbwSoCwDFc8Dz%2Byl6%2BzXeBTXgFRI53O/DML4E5hmMdqI81LVkCwGEcZaseZU4QAIAoAeBI9j9c7z8h/CQAHMzOG3bn2eAlAeB49tyze04FrxAADmm3bbvbPPAWAsBR7bNz95kE/hcB4MB22Lw7zADv409BMMGSD/da/RydGwAT3H4X2/4M4AbAKDe4Clj9jOEGwCjX3s62P5O4ATCWv%2B0MrxMA5nt3Cex9ZhMAWn4ZA0ufDgEAiPJLYIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAqH8Br2QJhWKBn1EAAAAASUVORK5CYII%3D%22%2C%20%22sizes%22%3A%20%22512x512%22%2C%20%22type%22%3A%20%22image/png%22%7D%2C%20%7B%22src%22%3A%20%22data%3Aimage/png%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAALQAAAC0CAIAAACyr5FlAAACq0lEQVR4nO3dsW7TYBhAUQfxBK0EGzMMTLz/zsLEwDMwdMwchnZwSW6bpgoJ/c4Zm8r6Jd9%2B%2Bu248ubm5sNyHnd3v8905Nvbj2c6sjWvvTvTcXkDxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQNrvd7kyH/h//r9ya10wOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQO0sa77Nesec3kIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIHmX/SPWvGZykMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkLzL/hFrXjM5SOIgiYMkDpI4SOIgiYMkDpI4SOIgiYMkDpI4SOIgiYMkDpI4SOIgiYMkDpI4SOIgiYO02W63l14DV8rkIImDtPn%2B6fOl18CVMjlI4iC9v/QCrsLXXz/2f/jzy7d/v5KrMn3PcTCLtcmJzI3j2SzWZiYydM/xojJO%2BP23YWIcp53pgX2Mi%2BM153haH65WHvy1q5jWwUGzJked8v39Zu1AR0UzK46DqoOZVyhrg%2BI44U7XwU/nDI9Bcew7ZjZMnh%2Bj4%2BBp4iCJgyQO0ug4jrnumHNtsm9QHCdclw5/zmNQHKX6mDwz7s2K4/ib4sffaH/DfPH2wJzYN2tyLK/70x81NpaBcSynnuNpZSwz41hefqYHlrFMfsD4nqfPnzA9jnvD72cUcZCG7jk4hjhI4iCJg/QH7tGB0h7uSIUAAAAASUVORK5CYII%3D%22%2C%20%22sizes%22%3A%20%22180x180%22%2C%20%22type%22%3A%20%22image/png%22%7D%5D%7D">
<link rel="icon" type="image/png" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAgAAAAIACAIAAAB7GkOtAAAJfUlEQVR4nO3dsU5cVxRAURP5CxjJdK6dIlX+v3eTKkW+gWJK16RAcoOCCczMve/steoEDnrS2fc+NPju/v7Lp7Dz+XH1CCudTg+rR1jJ0189wkrxp//st9UDALCGAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAEQJAECUAABECQBAlAAARAkAQJQAAETdPT09rZ5hpdPpYfUIK53Pj6tHWMnTXz3CSp7+JzcAgCwBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiLq7v/+yeoaVzufH1SOsdDo9rB5hJU9/9QgrxZ/+MzcAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiLp7enpaPcNKp9PD6hFWOp8fV4+wkqe/eoSVPP1PbgAAWQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQdXd//2X1DCudz4+rR1jpdHpYPcJKnv7qEVaKP/1nbgAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFECABAlAABRAgAQJQAAUQIAECUAAFF3P378WD0DAAu4AQBECQBAlAAARAkAQJQAAEQJAECUAABECQBA1N33r99WzwDAAm4AAFECABAlAABRAgAQJQAAUQIAECUAAFGfVw8AN/XHP3+9/h/8/fuft5kElvNBMOb75dL/L2LAbALAWO/e+y8pASMJANNccO+/pARM4pfAjHLV7X+Drw+35AbAEDdeza4CDOAGwAS3P5i7CjCAGwDHtnwRuwpwXG4AHNjy7b/JDPA+AsBR7bN595kE/hcB4JB227m7zQNvIQAcz57bds+p4BUCwMHsvGd3ng1eEgCOZP8Nu/+E8JMAAEQJAIdxlMP1UeYEAeAYjrVVjzUtWf5BGHJe+eyuxU2KPwXBAVxqL7/xzzbc+NvBKgLA7i6yjt+xi1d9X7gZr4AY7t0r+Pl/9FKIwfwSmMk+fgB3hGcwAWBrHzmAX2p3f+TruECwMwFgpsue3N0DGEkAGOga+1oDmEcA2NeM9yczfgpGEgCmud5R3SWAYQQAIEoAGOXah3SXACYRADY16dX5pJ+FSQSAOW5zPHcJYAwBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAWCO23zg1sd6GUMA2NSkD9xO+lmYRAAY5drHc8d/JhEAgCgBYJrrHdId/xlGANjXjFfnM34KRhIABrrGUd3xn3kEgJkuu69tf0YSALb2kfcnl9raH/k63v+wMwFgso83wNmfwT6vHgCu63mDv+MkbvUz3t33r99WzwC/cKld/MYM3PjbwSoCwDFc8Dz+yl6+zXeBTXgFRI53O/DML4E5hmMdqI81LVkCwGEcZaseZU4QAIAoAeBI9j9c7z8h/CQAHMzOG3bn2eAlAeB49tyze04FrxAADmm3bbvbPPAWAsBR7bNz95kE/hcB4MB22Lw7zADv409BMMGSD/da/RydGwAT3H4X2/4M4AbAKDe4Clj9jOEGwCjX3s62P5O4ATCWv+0MrxMA5nt3Cex9ZhMAWn4ZA0ufDgEAiPJLYIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAKAEAiBIAgCgBAIgSAIAoAQCIEgCAqH8Br2QJhWKBn1EAAAAASUVORK5CYII=">
<link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALQAAAC0CAIAAACyr5FlAAACq0lEQVR4nO3dsW7TYBhAUQfxBK0EGzMMTLz/zsLEwDMwdMwchnZwSW6bpgoJ/c4Zm8r6Jd9++u248ubm5sNyHnd3v8905Nvbj2c6sjWvvTvTcXkDxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQxEESB0kcJHGQNrvd7kyH/h//r9ya10wOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQOkjhI4iCJgyQO0sa77Nesec3kIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIImDJA6SOEjiIHmX/SPWvGZykMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkMRBEgdJHCRxkLzL/hFrXjM5SOIgiYMkDpI4SOIgiYMkDpI4SOIgiYMkDpI4SOIgiYMkDpI4SOIgiYMkDpI4SOIgiYO02W63l14DV8rkIImDtPn+6fOl18CVMjlI4iC9v/QCrsLXXz/2f/jzy7d/v5KrMn3PcTCLtcmJzI3j2SzWZiYydM/xojJO+P23YWIcp53pgX2Mi+M153haH65WHvy1q5jWwUGzJked8v39Zu1AR0UzK46DqoOZVyhrg+I44U7XwU/nDI9Bcew7ZjZMnh+j4+Bp4iCJgyQO0ug4jrnumHNtsm9QHCdclw5/zmNQHKX6mDwz7s2K4/ib4sffaH/DfPH2wJzYN2tyLK/70x81NpaBcSynnuNpZSwz41hefqYHlrFMfsD4nqfPnzA9jnvD72cUcZCG7jk4hjhI4iCJg/QH7tGB0h7uSIUAAAAASUVORK5CYII=">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,'Segoe UI',Roboto,sans-serif;background:#fff;color:#1a1a1e;padding:10px;max-width:520px;margin:0 auto;min-height:100vh}
.sp{user-select:none;-webkit-user-select:none;-webkit-touch-callout:none}
.sp button{font:inherit}
.sp .hud{display:flex;gap:8px;margin-bottom:8px;flex-wrap:wrap}
.sp .cell{border:1px solid #d9d9e0;border-radius:10px;padding:6px 12px;min-width:76px;display:flex;flex-direction:column;background:#fff}
.sp .cell .lbl{font-size:12px;color:#7a7b85;line-height:16px}
.sp .cell .val{font-size:17px;font-weight:600;font-variant-numeric:tabular-nums;line-height:22px}
.sp .cell.speed{margin-left:auto;align-items:flex-end;min-width:96px}
.sp .cell.speed .val{font-size:28px;line-height:30px}
.sp .dist{height:8px;border-radius:99px;background:#ececf0;overflow:hidden;margin-bottom:8px;position:relative}
.sp .dfill{height:100%;width:0%;background:#1a1a1e;border-radius:99px;transition:width 100ms linear}
.sp .dflag{position:absolute;right:0;top:0;bottom:0;width:14px;background:repeating-conic-gradient(#1a1a1e 0% 25%,transparent 0% 50%);background-size:7px 7px}
.sp .cvwrap{position:relative;border-radius:12px;overflow:hidden;border:1px solid #d9d9e0;background:#fff}
.sp canvas{display:block;width:100%;height:auto;touch-action:none}
.sp .overlay{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:12px;background:rgba(255,255,255,0.88);backdrop-filter:blur(3px);text-align:center;padding:16px}
.sp .overlay.hidden{display:none}
.sp h2{font-size:22px;font-weight:600}
.sp p{font-size:14px;color:#4a4b55;line-height:22px;max-width:420px}
.sp .flag{width:56px;height:40px;border-radius:6px;border:1px solid #d9d9e0;background:repeating-conic-gradient(#1a1a1e 0% 25%,#fff 0% 50%);background-size:14px 14px}
.sp .keys{display:flex;gap:6px;flex-wrap:wrap;justify-content:center}
.sp .key{border:1px solid #d9d9e0;border-radius:6px;padding:2px 8px;font-size:12px;color:#5b5c66;background:#f4f4f7}
.sp .btn{border:none;border-radius:10px;padding:12px 32px;font-size:16px;font-weight:600;cursor:pointer;background:#1a1a1e;color:#fff}
.sp .btn:active{opacity:.85}
.sp .nitrorow{display:flex;align-items:center;gap:8px;margin-top:8px}
.sp .nitrorow .lbl{font-size:12px;color:#7a7b85}
.sp .nbar{flex:1;height:8px;border-radius:99px;background:#ececf0;overflow:hidden}
.sp .nfill{height:100%;width:60%;border-radius:99px;background:#3b6fd4;transition:width 80ms linear}
.sp .dots{font-size:12px;color:#7a7b85;min-width:96px;text-align:right;font-variant-numeric:tabular-nums}
.sp .touch{display:none;gap:8px;margin-top:12px}
.sp .tbtn{flex:1;border:1px solid #d9d9e0;border-radius:10px;background:#f4f4f7;color:#1a1a1e;padding:16px 0;font-size:15px;font-weight:600;touch-action:none;-webkit-tap-highlight-color:transparent}
.sp .tbtn:active{background:#e2e2e8}
.sp .tbtn.acc{background:#1a1a1e;color:#fff}
.sp .hint{margin-top:8px;font-size:12px;color:#a0a1ab;text-align:center}
.sp .install{margin-top:10px;font-size:12px;color:#7a7b85;background:#f4f4f7;border-radius:8px;padding:8px 12px;max-width:420px;line-height:18px}
@media (pointer:coarse){.sp .touch{display:flex}.sp .hint{display:none}}
@media (prefers-color-scheme:dark){body{background:#141416;color:#f2f2f5}.sp .cell{background:#1c1c20;border-color:#333338}.sp .cvwrap{background:#1c1c20;border-color:#333338}.sp .overlay{background:rgba(20,20,24,0.88)}.sp .key{background:#232329;border-color:#333338;color:#9a9aa4}.sp .tbtn{background:#232329;border-color:#333338;color:#f2f2f5}.sp .tbtn:active{background:#2e2e35}.sp .dist,.sp .nbar{background:#232329}.sp .install{background:#1c1c20;color:#9a9aa4}p{color:#b9bac2 !important}.sp p{color:#b9bac2}}
</style>
</head>
<body>

<div class="sp">
  <div class="hud">
    <div class="cell"><span class="lbl">Дистанция</span><span class="val" id="sDist">0 / 5000 м</span></div>
    <div class="cell"><span class="lbl">Шашки</span><span class="val" id="sTok">0</span></div>
    <div class="cell"><span class="lbl">Время</span><span class="val" id="sTime">0:00.0</span></div>
    <div class="cell speed"><span class="val" id="sSpd">0</span><span class="lbl">км/ч</span></div>
  </div>
  <div class="dist"><div class="dfill" id="dfill"></div><div class="dflag"></div></div>
  <div class="cvwrap">
    <canvas id="cv" width="460" height="560"></canvas>
    <div class="overlay" id="menu">
      <div class="flag"></div>
      <h2>Шашечный спринт</h2>
      <p>Догоните клетчатый флаг: 5 км трассы, соперники в трёх полосах и «шашечки» — собирайте их, чтобы заряжать нитро. Три аварии — сход (DNF).</p>
      <div class="keys"><span class="key">← →</span><span class="key">полоса</span><span class="key">пробел</span><span class="key">нитро</span></div>
      <button class="btn" id="btnStart">Старт</button>
      <div class="install">Чтобы добавить игру на экран «Домой»: откройте эту страницу в браузере телефона → меню «Поделиться» → «На экран «Домой»». Игра запустится в полноэкранном режиме, как приложение.</div>
    </div>
    <div class="overlay hidden" id="fin">
      <div class="flag"></div>
      <h2 id="finTitle">Финиш!</h2>
      <p id="finText"></p>
      <button class="btn" id="btnRestart">Ещё раз</button>
    </div>
  </div>
  <div class="nitrorow">
    <span class="lbl">Нитро</span>
    <div class="nbar"><div class="nfill" id="nfill"></div></div>
    <span class="dots" id="dots">● ● ●</span>
  </div>
  <div class="touch">
    <button class="tbtn" id="tL">◀ Полоса</button>
    <button class="tbtn" id="tN">Нитро</button>
    <button class="tbtn" id="tR">Полоса ▶</button>
  </div>
  <div class="hint">← → или A/D — смена полосы, пробел — нитро. На мобильном — кнопки ниже.</div>
</div>

<script>
var cv=document.getElementById('cv'),ctx=cv.getContext('2d'),W=460,H=560;
function css(v){return getComputedStyle(document.documentElement).getPropertyValue(v).trim()}
function rgba(tok,a){var c=css(tok).trim();if(c[0]==='#'){var n=parseInt(c.slice(1),16);return 'rgba('+((n>>16)&255)+','+((n>>8)&255)+','+(n&255)+','+a+')'}var m=c.match(/[\d.]+/g);if(m&&m.length>=3)return 'rgba('+m[0]+','+m[1]+','+m[2]+','+a+')';return c}
var ROAD_X=34,LANES=3,LANE_W=(W-ROAD_X*2)/LANES;
function laneX(i){return ROAD_X+LANE_W*(i+0.5)}
var LIGHT=(function(){var v=css('--kimi-color-surface-strong').trim();var n=parseInt(v.slice(1),16);return ((n>>16&255)+(n>>8&255)+(n&255))/3>128})();
if(!LIGHT){document.body.style.background='#141416'}
var ASPHALT=LIGHT?'#c9cad1':'#2a2a2e',ASPIN=LIGHT?'#dcdee4':'#333338',TXT=LIGHT?'#1a1a1e':'#f2f2f5',GRASS=LIGHT?'rgba(60,160,90,0.14)':'rgba(60,160,90,0.12)';
var COL={asphalt:ASPHALT,asphaltIn:ASPIN,line:LIGHT?'rgba(20,20,25,0.75)':'rgba(240,240,245,0.8)',grass:GRASS,p:'#3b6fd4',r:['#d4453b','#3fae5a','#8b5fd6','#8d8d96'],dark:TXT,ui:TXT,muted:LIGHT?'#5b5c66':'#9a9aa4'};
var GOAL=5000,keys={},state='menu',countT=0,goFlash=0;
var pl,obs,toks,dist,time,tokens,nitro,invuln,dashOff,nextSpawn,nextTok,shake;
function reset(){pl={x:laneX(1),lane:1,speed:0};obs=[];toks=[];dist=0;time=0;tokens=0;nitro=60;invuln=0;dashOff=0;nextSpawn=500;nextTok=260;shake=0;obs.crash=0}
reset();
addEventListener('keydown',function(e){if(['ArrowLeft','ArrowRight','ArrowUp','ArrowDown','Space'].indexOf(e.code)>=0)e.preventDefault();keys[e.code]=true;if(state==='over'&&e.code==='Enter')start()});
addEventListener('keyup',function(e){keys[e.code]=false});
function bindHold(id,on,off){var el=document.getElementById(id);var d=function(e){e.preventDefault();on()},u=function(e){e.preventDefault();off()};el.addEventListener('pointerdown',d);el.addEventListener('pointerup',u);el.addEventListener('pointercancel',u);el.addEventListener('pointerleave',u)}
bindHold('tL',function(){keys.ArrowLeft=true},function(){keys.ArrowLeft=false});
bindHold('tR',function(){keys.ArrowRight=true},function(){keys.ArrowRight=false});
bindHold('tN',function(){keys.Space=true},function(){keys.Space=false});
var AC=null;function initAudio(){try{if(!AC&&window.AudioContext)AC=new AudioContext();if(AC&&AC.state==='suspended')AC.resume()}catch(e){}}
function beep(f,d,type,g){try{if(!AC)return;var o=AC.createOscillator(),gn=AC.createGain();o.type=type||'square';o.frequency.value=f;gn.gain.setValueAtTime(g||0.05,AC.currentTime);gn.gain.exponentialRampToValueAtTime(0.001,AC.currentTime+d);o.connect(gn);gn.connect(AC.destination);o.start();o.stop(AC.currentTime+d)}catch(e){}}
document.getElementById('btnStart').addEventListener('click',start);
document.getElementById('btnRestart').addEventListener('click',start);
function start(){initAudio();reset();state='count';countT=3.99;document.getElementById('menu').classList.add('hidden');document.getElementById('fin').classList.add('hidden')}
function fmt(t){var m=Math.floor(t/60),s=t-m*60;return m+':'+(s<10?'0':'')+s.toFixed(1)}
function crash(){obs.crash++;invuln=1.4;shake=0.6;pl.speed*=0.25;beep(90,0.3,'sawtooth',0.09);if(obs.crash>=3)end(false)}
function end(win){state='over';var title=win?'Финиш!':'Сход (DNF)';var stars='';if(win){var score=time+tokens*0.5;stars=score<55?'★★★':score<70?'★★☆':'★☆☆'}
 document.getElementById('finTitle').textContent=title;
 document.getElementById('finText').innerHTML=win?('Время: <b>'+fmt(time)+'</b> · Шашки: <b>'+tokens+'</b> · Оценка: <b>'+stars+'</b>'):'Болид не выдержал ударов. До флага осталось '+(GOAL-Math.floor(dist))+' м. Попробуйте ещё раз!';
 document.getElementById('fin').classList.remove('hidden')}
function spawnObstacle(){var lane=Math.floor(Math.random()*LANES);obs.push({x:laneX(lane),y:-70,c:COL.r[Math.floor(Math.random()*4)]});if(Math.random()<0.35){var l2=(lane+(Math.random()<0.5?1:2))%LANES;obs.push({x:laneX(l2),y:-70-40-Math.random()*60,c:COL.r[Math.floor(Math.random()*4)]})}}
function spawnTok(){var lane=Math.floor(Math.random()*LANES),n=2+Math.floor(Math.random()*3);for(var i=0;i<n;i++)toks.push({x:laneX(lane),y:-30-i*44,got:false})}
function update(dt){
 if(state==='count'){var p=Math.ceil(countT);countT-=dt;if(Math.ceil(countT)<p&&countT>0)beep(440,0.12);if(countT<=0){state='race';goFlash=0.8;beep(880,0.35)}return}
 if(state!=='race')return;
 time+=dt;goFlash=Math.max(0,goFlash-dt);invuln=Math.max(0,invuln-dt);shake=Math.max(0,shake-dt*2.5);
 var left=keys.ArrowLeft||keys.KeyA,right=keys.ArrowRight||keys.KeyD,nit=keys.Space&&nitro>2;
 if(left&&!pl.lk){pl.lane=Math.max(0,pl.lane-1);pl.lk=true}if(!left)pl.lk=false;
 if(right&&!pl.rk){pl.lane=Math.min(LANES-1,pl.lane+1);pl.rk=true}if(!right)pl.rk=false;
 pl.x+=(laneX(pl.lane)-pl.x)*Math.min(1,dt*9);
 var maxSp=nit?520:400;if(nit){nitro=Math.max(0,nitro-30*dt)}else nitro=Math.min(100,nitro+4*dt);
 pl.speed+=(maxSp-pl.speed)*dt*0.55;pl.speed=Math.min(maxSp,pl.speed);
 dist+=pl.speed*dt*0.22;dashOff=(dashOff+pl.speed*dt)%48;
 if(dist>nextSpawn){spawnObstacle();nextSpawn=dist+260+Math.random()*220-Math.min(120,dist*0.02)}
 if(dist>nextTok){spawnTok();nextTok=dist+380+Math.random()*300}
 var i;
 for(i=obs.length-1;i>=0;i--){var o=obs[i];o.y+=(pl.speed*0.72+70)*dt;if(o.y>H+80){obs.splice(i,1);continue}
  if(invuln<=0&&Math.abs(o.x-pl.x)<24&&Math.abs(o.y-(H-90))<40){obs.splice(i,1);crash()}}
 for(i=toks.length-1;i>=0;i--){var t=toks[i];t.y+=pl.speed*dt;if(t.got||t.y>H+30){toks.splice(i,1);continue}
  if(Math.abs(t.x-pl.x)<26&&Math.abs(t.y-(H-90))<42){t.got=true;tokens++;nitro=Math.min(100,nitro+16);toks.splice(i,1);beep(1320,0.08,'sine',0.06)}}
 if(dist>=GOAL)end(true)}
function drawCar(x,y,color,me,flash){ctx.save();ctx.translate(x,y);
 ctx.fillStyle=COL.dark;ctx.fillRect(-11,-21,22,5);ctx.fillRect(-11,16,22,5);
 ctx.fillStyle=color;ctx.beginPath();ctx.moveTo(0,-22);ctx.lineTo(6,-9);ctx.lineTo(6,14);ctx.lineTo(-6,14);ctx.lineTo(-6,-9);ctx.closePath();ctx.fill();
 ctx.fillStyle=COL.dark;ctx.beginPath();ctx.arc(0,-2,3.4,0,7);ctx.fill();
 if(me&&flash){ctx.globalAlpha=0.5+0.5*Math.sin(performance.now()/60);ctx.fillStyle='#fff';ctx.beginPath();ctx.moveTo(0,-22);ctx.lineTo(6,-9);ctx.lineTo(6,14);ctx.lineTo(-6,14);ctx.lineTo(-6,-9);ctx.closePath();ctx.fill()}
 ctx.restore()}
function drawTok(t){var s=13;for(var r=0;r<2;r++)for(var c=0;c<2;c++){ctx.fillStyle=(r+c)%2?COL.dark:'#fff';ctx.fillRect(t.x-s/2+c*s/2,t.y-s/2+r*s/2,s/2,s/2)}ctx.strokeStyle=LIGHT?'#999':'#555';ctx.lineWidth=1;ctx.strokeRect(t.x-s/2,t.y-s/2,s,s)}
function draw(){ctx.clearRect(0,0,W,H);ctx.fillStyle=COL.grass;ctx.fillRect(0,0,W,H);
 ctx.save();if(shake>0)ctx.translate((Math.random()-0.5)*shake*7,(Math.random()-0.5)*shake*7);
 ctx.fillStyle=COL.asphalt;ctx.fillRect(ROAD_X-6,0,W-ROAD_X*2+12,H);
 ctx.fillStyle=COL.asphaltIn;ctx.fillRect(ROAD_X,0,W-ROAD_X*2,H);
 ctx.fillStyle=COL.line;ctx.fillRect(ROAD_X,0,3,H);ctx.fillRect(W-ROAD_X-3,0,3,H);
 ctx.fillStyle=LIGHT?'rgba(60,60,70,0.5)':'rgba(150,150,160,0.5)';
 for(var l=1;l<LANES;l++){var x=ROAD_X+LANE_W*l;for(var y=-48+dashOff;y<H;y+=48)ctx.fillRect(x-2,y,4,26)}
 var i;for(i=0;i<toks.length;i++)drawTok(toks[i]);
 for(i=0;i<obs.length;i++)drawCar(obs[i].x,obs[i].y,obs[i].c,false,false);
 drawCar(pl.x,H-90,COL.p,true,invuln>0);
 ctx.restore();
 if(state==='count'){var n=Math.ceil(countT);ctx.fillStyle='rgba(120,120,130,0.55)';ctx.beginPath();ctx.arc(W/2,H/2,58,0,7);ctx.fill();ctx.fillStyle=COL.ui;ctx.font='500 84px system-ui,sans-serif';ctx.textAlign='center';ctx.textBaseline='middle';ctx.fillText(n,W/2,H/2+2)}
 if(goFlash>0){ctx.globalAlpha=Math.min(1,goFlash);ctx.fillStyle='#2fae54';ctx.font='500 64px system-ui,sans-serif';ctx.textAlign='center';ctx.textBaseline='middle';ctx.fillText('Старт!',W/2,H/2);ctx.globalAlpha=1}}
var sDist=document.getElementById('sDist'),sTok=document.getElementById('sTok'),sTime=document.getElementById('sTime'),sSpd=document.getElementById('sSpd'),dfill=document.getElementById('dfill'),nfill=document.getElementById('nfill'),dots=document.getElementById('dots');
function hud(){sDist.textContent=Math.min(GOAL,Math.floor(dist))+' / '+GOAL+' м';sTok.textContent=tokens;sTime.textContent=fmt(time);sSpd.textContent=Math.round(pl.speed*0.85);dfill.style.width=Math.min(100,dist/GOAL*100)+'%';nfill.style.width=nitro+'%';
 var left=3-obs.crash,d='';for(var i=0;i<3;i++)d+=(i<left?'● ':'○ ');dots.textContent=d.trim();dots.style.color=left===1?'#d43a3a':(LIGHT?'#5b5c66':'#9a9aa4')}
var lastT=0;function loop(t){var dt=Math.min(0.033,(t-lastT)/1000||0);lastT=t;update(dt);draw();hud();requestAnimationFrame(loop)}
requestAnimationFrame(loop);
</script>
</body>
</html>