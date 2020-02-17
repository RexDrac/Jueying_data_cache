critic-activation-fn: ['relu', 'relu', 'None']
expert-num: 4
total-step-num: 2500000000
filter-torque: False
test-num: 4
actor-weight-decay: 1e-06
render-eval: False
gating-layer-size: [128, 128]
HLC-frequency: 25
Physics-frequency: 1000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-train-time: 10
task-weight: 0.2
replay-start-size: 10000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
n-step: 1
state-dim: 25
max-path-num: 20
actor-lr: 0.0003
critic-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
critic-layer-size: [256, 256]
max-test-time: 10
squash-action: True
max-episode-num: 5000000
imitation-weight: 0.4
rollout-step-num: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
bullet-default-PD: False
epoch-step-num: 5000000
record-start-size: 10000.0
actor-l2-reg: 0.0003
LLC-frequency: 500
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-buffer-size: 1000000
prioritized-exp-replay: True
tau: 0.001
batch-size: 128
gating-mask: [[1.0, 1.0, 1.0, 1.0]]
joint-interpolation: True
reward-scale: 0.1
filter-action: True
goal-weight: 0.4
critic-lr: 0.0003
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
interpolation: False
gamma: 0.986
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
loss-output-bound-coeff: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
actor-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
dsr-gait-period: 0.6
loss-output-diff-coeff: 0
replay-ratio: 1
dsr-gait-freq: 1.667
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-path-step: 5000
action-dim: 12
env-id: HumanoidBalanceFilter-v0
epoch-num: 500
critic-l2-reg: 0.0003
