class Butterfly:
    def __init__(self, x: float, no_iterations: int):
        self.x = x
        self.no_iterations = no_iterations

    def period_zero(self):
        list_results = []
        i = 0
        while i < self.no_iterations:
            sol = (2 * self.x**2) - 1
            list_results.append(round(sol, 4))
            self.x = sol
            i += 1
        return list_results

    def period_one(self):
        list_results = []
        i = 0
        while i < self.no_iterations:
            sol = (self.x**2) - 1
            list_results.append(round(sol, 4))
            self.x = sol
            i += 1
        return list_results
